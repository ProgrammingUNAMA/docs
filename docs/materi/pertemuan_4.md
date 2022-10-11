## 1. Kustomisasi VScode

#### Thema

> file> Preferences> Color Theme
> ctrl + k + t

#### Icon
> file> Preferences> File Icon Theme

'Material Icon Theme'

#### Product Icon Theme (sidebar)
> file> Preferences> Product Icon Theme

#### Extensions
1. Discord Presence by [Crawl](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode)
	- [Customize Discord Presence](https://www.youtube.com/watch?v=k3IJwfirovE)

3. Todo Tree by  [Gruntfuggly](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

## 2. Software
- XAMPP (8.1.10 / PHP 8.1.10) https://www.apachefriends.org/download.html
- Composer https://getcomposer.org/
- Node.JS (LTS) https://nodejs.org/en/

Tambahan:
- VSCode https://code.visualstudio.com/
- GitDesktop https://desktop.github.com/

## 3. VSCode Extensions
## 4. Membuat Project Laravel & Vue
Sumber Belajar Utama:
- Materi dari  Dosen UNAMA (Abdul Rahim, S.Kom, M.Kom) | https://s.id/mweb2unama
- WPU (Laravel) | https://www.youtube.com/watch?v=HqAMb6kqlLs&list=PLFIM0718LjIWiihbBIq-SWPU6b6x21Q_2&ab_channel=WebProgrammingUNPAS
- Dokumentasi Laravel | https://laravel.com/docs/9.x

Buat sebuat Folder baru (misal: ProgrammingUNAMA) dan masuk kedalam folder tersebut.
#### 1. membuat project laravel-blade (default):
- sumber:
	- https://laravel.com/docs/9.x
	- https://laravel.com/docs/9.x/starter-kits#laravel-breeze-installation
1. membuat project laravel (terminal):
	a. cara 1
 ``composer create-project laravel/laravel example-app``
 b. cara 2
 install laravel pada computer
 ``composer global require laravel/installer``
 lalu buat porject dengan perintah:
 ``laravel new example-app``

 2. install breeze authentication blade:
 ``composer require  laravel/breeze  --dev``
 ``php artisan  breeze:install``
 ~~``php artisan  migrate``~~ (tahap ini bisa di skip karena kita belum menambahkan database)
 ``npm install``
 ``npm run  dev`` (close browser dan terminal jika sudah berhasil)
 
 3. memulai development server
 ``php artisan serve`` 
#### 2. membuat project laravel-vue:
- sumber:
	- https://laravel.com/docs/9.x
	- https://laravel.com/docs/9.x/starter-kits#laravel-breeze-installation
1. membuat project laravel (terminal):
	a. cara 1
 ``composer create-project laravel/laravel example-app``
 b. cara 2
 install laravel pada composer
 ``composer global require laravel/installer``
 lalu buat porject dengan perintah:
 ``laravel new example-app``
 
 2. install breeze authentication blade:
 ``composer require  laravel/breeze  --dev``
 ``php artisan  breeze:install vue``
 ~~``php artisan  migrate``~~ (tahap ini bisa di skip karena kita belum menambahkan database)
 ``npm install``
 ``npm run  dev`` (close browser dan terminal jika sudah berhasil)
 
 3. memulai development server
  ``php artisan serve`` 
#### 3. membuat project vue:
- sumber
		- https://vuejs.org/guide/introduction.html
		- https://vitejs.dev/guide/
		
1. buat project vite dengan perintah (terminal):
``npm create vite@latest``
2. buat nama project yaitu "vue":
``√ Project name:`` vue
3. akan muncul beberapa pilihan framework seperti dibawah, silahkan pilih ``vue``:
>? Select a framework: » - Use arrow-keys. Return to submit.
   Vanilla
    Vue
    React
    Preact
    Lit
    Svelte
4. selanjutkan akan ada pilihan variant, silahkan pilih ``Customize with create-vue``:
>? Select a variant: » - Use arrow-keys. Return to submit.
   JavaScript
    TypeScript
    Customize with create-vue
    Nuxt
5. akan ada pilihan fitur untuk ditambahkan (silahkan pilih ``No`` untuk semuanya, kecuali ``Add Vue Router for Single Page Application development`` dipilih ``Yes``):
> Vue.js - The Progressive JavaScript Framework
√ Add TypeScript? ... No / Yes
√ Add JSX Support? ... No / Yes
√ Add Vue Router for Single Page Application development? ... No / Yes
√ Add Pinia for state management? ... No / Yes
√ Add Vitest for Unit Testing? ... No / Yes
√ Add Cypress for both Unit and End-to-End testing? ... No / Yes
√ Add ESLint for code quality? ... No / Yes
6. jalankan perintah berikut:
>  cd vue
  npm install
  npm run dev

## 5. Push Project ke Repository Github (Pribadi)

Push 3 project yang telah dibuat ke repository github pribadi masing-masing dengan nama repository:
1. laravel-blade
	didalam terminal masukan perintah:
		- ``git init``
		- ``git add .``
		- ``git commit -m "init"``
		- buat repositori di github dengan nama project **laravel-blade** (public)
		- ``git remote add origin (alamat repository)``
		- ``git branch -M main``
		- ``git push -u origin main``
		
2. laravel-vue
		didalam terminal masukan perintah:
		- ``git init``
		- ``git add .``
		- ``git commit -m "init"``
		- buat repositori di github dengan nama project **laravel-vue** (public)
		- ``git remote add origin (alamat repository)``
		- ``git branch -M main``
		- ``git push -u origin main``
3. vue
		didalam terminal masukan perintah:
		- ``git init``
		- ``git add .``
		- ``git commit -m "init"``
		- buat repositori di github dengan nama project **vue** (public)
		- ``git remote add origin (alamat repository)``
		- ``git branch -M main``
		- ``git push -u origin main``



