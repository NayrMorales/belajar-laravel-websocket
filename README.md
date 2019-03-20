# belajar-laravel-websocket
Belajar pemanfaatan websocket di laravel

Step by step :
- composer install
- npm install 
- php artisan serve
- php artisan websocket:serve
- Buka localhost:8000 pada tab baru
- Buka console web browser
- buka localhost:8000/laravel-websockets pada tab baru
- masukan masing-masing field dengan value: 

    - Channel : DemoChannel
    - Event : App\Events\WebSocket
    - Data : {"test":1}

- Teekan tombol Send Event