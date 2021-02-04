# vue3-cli-sinatra

## Create project with vue-cli
```
vue create vue3-cli-sinatra
```

### Copy this repos's file & dir in vue3-cli-sinatra dir

### Compiles and hot-reloads for development
```
cd vue3-cli-sinatra
bundle install
yarn
foreman start

# FrontEnd: http://localhost:5100
# BackEnd:  http://localhost:8080
```

### Compiles and minifies for production
```
cd vue3-cli-sinatra
bundle install
yarn
yarn build

# Start server
puma --dir=app --config=app/config/puma.rb --environment=production --port=80
# or
./start.sh

# http://localhost:8080
```
