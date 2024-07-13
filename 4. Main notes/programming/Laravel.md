---
title: laravel
date: 10-07-2024
tags:
  - webdev
  - php
  - incomplete
index: "[[webdev]]"
---

# Laravel
## External libraries
- UI:  [livewire](https://laravel-livewire.com/),[wireui](https://wireui.dev/)
## Migrations
### Table  relationships
This is an exemple on how you can define a relationship: 
```php
 Schema::create("doctors", function (Blueprint $table) {
            $table->id();
            $table->foreignId("user_id")->constrained()->cascadeOnDelete()->unique();
            $table->char("job", 35);
            $table->charset("crm", 9);
            $table->timestamps();
        });
```
Doctor should have a **one-to-one** relationship with the table `users`. To make this easier to work with, we also have to define this relationship in  both the User and Doctor model.
- users model
```php
public function doctor()
    {
        return $this->hasOne(Doctor::class);
    }
	```
- doctors model
```php
public function user()
    {
        return $this->hasOne(User::class);
    }
```
## Artisan
### Create model with migration
```bash
php artisan make:model Settings --migration
```

## Livewire
### Create a livewire component
#### Class and component in the same file:
- command:
```bash
php artisan make:volt counter --class
```
- output:
```php
<?php 
use Livewire\Volt\Component; 
new class extends Component {    
	public $count = 0;     
	public function increment()    
	{        
	$this->count++;    
	}
} 
?> 
<div>
	<h1>{{ $count }}</h1>    
	<button wire:click="increment">+</button>
</div>
```
#### Create normally 
- command:
```bash
php artisan make:livewire CreatePost
```
- output:
```php
<?php namespace App\Livewire; 
use Livewire\Component; 
class CreatePost extends Component{    
	public function render()    
	{        
	return view('livewire.create-post');    
	}
}
```
### How to use components
Lets say you created a component inside of ```/livewire/layout/```. The component is called navigation item, you can use it like this: 
```php
 <livewire:layout.navigation-item label="Médicos" icon="clipboard" ref=""/>
```
#### How to manage props in livewire
As you can see in the previous exemple we, are passing some props to the component. You can define the props inside of the mount method like this: 
```php
<?php

use Livewire\Volt\Component;

new class extends Component {
    public string $label;
    public string $ref;
    public string $icon;

    public function mount(
        string $label,
        string $ref,
        string $icon,
        string $action = null
    ): void {
        $this->label = $label;
        $this->ref = $ref;
        $this->icon = $icon;
    }
};
?>


<x-button flat black 2xl icon="{{ $icon }}" class="w-full">
    <a href="{{ $ref }}"  class="md:w-full md:text-left">{{ $label }}</a>
</x-button>
```
# References
- [docs](https://laravel.com/docs/11.x)