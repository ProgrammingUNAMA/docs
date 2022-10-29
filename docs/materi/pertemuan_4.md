# 1. Kustomisasi VScode

## Thema

> file> Preferences> Color Theme
> ctrl + k + t

## Icon
> file> Preferences> File Icon Theme

'Material Icon Theme'

## Product Icon Theme (sidebar)
> file> Preferences> Product Icon Theme

## Extensions
1. Discord Presence by [Crawl](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode)
	- [Customize Discord Presence](https://www.youtube.com/watch?v=k3IJwfirovE)

3. Todo Tree by  [Gruntfuggly](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

# 2. Software
- [XAMPP (8.1.10 / PHP 8.1.10)](https://www.apachefriends.org/download.html)
- [Composer](https://getcomposer.org/)
- [Node.JS](https://nodejs.org/en/)
- [VSCode](https://code.visualstudio.com/)

Tambahan:

- [GitDesktop](https://desktop.github.com/)
- [Obsidian](https://obsidian.md/)

# 3. VSCode Extensions
# 4. Membuat Project Laravel & Vue
Sumber Belajar Utama:

- Materi dari  Dosen UNAMA (Abdul Rahim, S.Kom, M.Kom) | [https://s.id/mweb2unama](https://s.id/mweb2unama)
- WPU (Laravel) | [youtube WPU](https://www.youtube.com/watch?v=HqAMb6kqlLs&list=PLFIM0718LjIWiihbBIq-SWPU6b6x21Q_2&ab_channel=WebProgrammingUNPAS)
- Dokumentasi Laravel | [Docs](https://laravel.com/docs/9.x)

Buat sebuat Folder baru (misal: ProgrammingUNAMA) dan masuk kedalam folder tersebut.
## 4.1 membuat project laravel-blade (default):
- sumber:
	- https://laravel.com/docs/9.x
	- https://laravel.com/docs/9.x/starter-kits#laravel-breeze-installation
1. membuat project laravel (terminal):
   
	a. cara 1 <br>
	```composer create-project laravel/laravel example-app```

	b. cara 2 <br>
	install laravel pada computer <br>
	```composer global require laravel/installer``` <br>
	lalu buat porject dengan perintah: <br>
	```laravel new example-app```

1. install breeze authentication blade:
```php
composer require  laravel/breeze --dev
php artisan  breeze:install
php artisan  migrate //tahap ini bisa di skip karena kita belum menambahkan database
npm install
npm run  dev //close browser dan terminal jika sudah berhasil
```
 
1. memulai development server
```php artisan serve```
## 4.2 membuat project laravel-vue:
- sumber:
	- https://laravel.com/docs/9.x
	- https://laravel.com/docs/9.x/starter-kits#laravel-breeze-installation
  
1. membuat project laravel (terminal):
   
	a. cara 1 <br>
	```composer create-project laravel/laravel example-app```

	b. cara 2 <br>
	install laravel pada composer <br>
	```composer global require laravel/installer``` <br>
	lalu buat porject dengan perintah: <br>
	```laravel new example-app```
 
2. install breeze authentication blade:
   
```php
composer require  laravel/breeze --dev
php artisan  breeze:install vue
php artisan  migrate //tahap ini bisa di skip karena kita belum menambahkan database
npm install
npm run  //close browser dan terminal jika sudah berhasil
```
 
 1. memulai development server
  ```php artisan serve``` 
## 4.2 membuat project vue:

- sumber
    - [https://vuejs.org/guide/introduction.html](https://vuejs.org/guide/introduction.html)
    - [https://vitejs.dev/guide/](https://vitejs.dev/guide/)
		
1. buat project vite dengan perintah (terminal):
   
```shell
npm create vite@latest
```

2. buat nama project yaitu "vue":

```shell
√ Project name: vue
```
3. akan muncul beberapa pilihan framework seperti dibawah, silahkan pilih ``vue``:
   
```shell
? Select a framework: » - Use arrow-keys. Return to submit.
    Vanilla
    Vue
    React
    Preact
    Lit
    Svelte
```
1. selanjutkan akan ada pilihan variant, silahkan pilih ``Customize with create-vue``:
>? Select a variant: » - Use arrow-keys. Return to submit.
   JavaScript
    TypeScript
    Customize with create-vue
    Nuxt
5. akan ada pilihan fitur untuk ditambahkan (silahkan pilih ``No`` untuk semuanya, kecuali ``Add Vue Router for Single Page Application development`` dipilih ``Yes``):
   
```shell
Vue.js - The Progressive JavaScript Framework
√ Add TypeScript? ... No / Yes
√ Add JSX Support? ... No / Yes
√ Add Vue Router for Single Page Application development? ... No / Yes
√ Add Pinia for state management? ... No / Yes
√ Add Vitest for Unit Testing? ... No / Yes
√ Add Cypress for both Unit and End-to-End testing? ... No / Yes
√ Add ESLint for code quality? ... No / Yes
```
6. jalankan perintah berikut:

```shell
cd vue
npm install
npm run dev
```

# 5. Push Project ke Repository Github (Pribadi)

Push 3 project yang telah dibuat ke repository github pribadi masing-masing dengan nama repository:

1. laravel-blade
	didalam terminal masukan perintah:<br>
		- ``git init`` <br>
		- ``git add .`` <br>
		- ``git commit -m "init"`` <br>
		- buat repositori di github dengan nama project **laravel-blade** (public) <br>
		- ``git remote add origin (alamat repository)`` <br>
		- ``git branch -M main`` <br>
		- ``git push -u origin main`` <br>
		
2. laravel-vue
		didalam terminal masukan perintah:<br>
		- ``git init`` <br>
		- ``git add .`` <br>
		- ``git commit -m "init"`` <br>
		- buat repositori di github dengan nama project **laravel-vue** (public) <br>
		- ``git remote add origin (alamat repository)`` <br>
		- ``git branch -M main`` <br>
		- ``git push -u origin main`` <br>
3. vue
		didalam terminal masukan perintah:<br>
		- ``git init`` <br>
		- ``git add .`` <br>
		- ``git commit -m "init"`` <br>
		- buat repositori di github dengan nama project **vue** (public) <br>
		- ``git remote add origin (alamat repository)`` <br>
		- ``git branch -M main`` <br>
		- ``git push -u origin main`` <br>


