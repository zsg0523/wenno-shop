## Laravel Shop

1 composer install
2 php artisan key:generate
3 php artisan migrate --seed
4 npm install cross-env --save-dev
5 yarn install
6 npm run dev


如果NPM一直不行，全删了重新安装
1 rm -rf node_modules
2 rm package-lock.json
3 npm cache clear --force
4 npm install