# warsawjs-workshop-49-vue
WarsawJS workshop, live coding - https://codesandbox.io/s/warsawjs-workshop-49-vue-j7wn0

### Project setup
```
# fork & clone https://github.com/janhorubala/warsawjs-workshop-49-vue
cd warsawjs-workshop-49-vue
# install vue cli
yarn global add @vue/cli
# create default project
vue create warsawjs-workshop-49-vue .
# setup tailwind https://flaviocopes.com/vue-tailwind/
yarn add tailwindcss
# add dotenv
yarn add dotenv
```
### Structure
- `/` - home page - list of posts
- `/add` - create post
- `/post/:postId` - show specific post

### Components
- `Home` - show all posts
- `AppBar` - login & logout, routes
- `Post` - show specific post
- `Add` - creating post

### Additional
- vuex - `auth.js`, `blog.js`
- router - just `index.js`

### Schedule
- home view - simply load data from spreadsheet
- import gapi.js
- install vuex
- move logic to vuex
- install router
- setup all routes
- implement auth
- router guards
- transitions (animation)
- modal (slots)
- routes (mixin)
- deploy to netlify
