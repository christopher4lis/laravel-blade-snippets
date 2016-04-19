# laravel-blade-snippets 
A library of sublime snippets for Laravel Blade.

##Installation
###Mac
1. Clone the repo to your Sublime user packages folder:
  - `/Users/User/Library/Application Support/Sublime Text 3/Packages/User/`
2. Restart Sublime Text if snippets aren't being read after install.

##Usage
|  Trigger   	|  Result |
|:--------------|-------------------------------------------------|
|  if        	|  `@if (condition) @endif`						  |
|  elseif       |  `@elseif (condition)`						  | 
|  else        	|  `@else` 										   |
|  extends    	|  `@extends('bladeFile: String')`           	  |
|  foreach      |  `@foreach () ... @endforeach` 				  | 
|  section		|  `@section('sectionName: String')`         	  |
|  stop     	|  `@stop`                                        |
|  unesc        |  `{!! unescaped data !!}` 					  |
|  yield        |  `@yield('name: String')` 					  |
