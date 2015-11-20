# How to use
0. Open the **Terminal** app
1. `docker-machine start default`
2. `docker-machine ssh default`
3. `git clone https://github.com/itrufeng/laravel.git laravel`
4. `cd laravel && docker build -t laravel ./`
5. `docker run -p 80:80 --name laravel_instance laravel`
6. ```open http://`docker-machine ip default````
7. Have a coffee!


