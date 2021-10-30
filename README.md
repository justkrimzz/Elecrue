![Elecrue Banner](https://user-images.githubusercontent.com/63385587/135675383-1c74f040-d8a9-49a4-a035-a0fcc4edac0c.png)

<div align="center">
<a href="https://badge.fury.io/js/elecrue" target="_blank" ><img src="https://badge.fury.io/js/elecrue.svg" alt="npm version"/></a>
<img src="https://img.shields.io/badge/Electron-2B2E3A?style=for-the-badge&logo=electron&logoColor=9FEAF9"/>
<img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
</div>

# What does it do?
Elecrue is a boilerplate generator for electron. It generates boilercode for react or vue, with bootstrap or tailwindcss.

# Current Templates
```
1. react-electron-js
2. react-electron-ts
3. react-electron-tailwind-js
4. react-electron-tailwind-ts
5. react-electron-bootstrap-js
6. react-electron-bootstrap-ts
7. vue-electron-js
8. vue-electron-ts
9. vue-electron-tailwind-js
10. vue-electron-tailwind-ts
11. vue-electron-bootstrap-js
12. vue-electron-bootstrap-ts
```

# Why does Elecrue don't use IPC?
From my experience connecting electron to react or vue is a hard thing, So I found a much easier and reliable solution to this problem. By creating an express server in electron file we can make endpoints for our react or vue application to hit, and when the app requests those endpoints it will trigger an event. By doing that we can do all the work that we can't do in react or vue. Think of it as a function in another file, but without calling you are making a get request to the server to trigger that function.

## How to install it?
```
  npm i -g elecrue
```
## How to use it?
![Elecrue Terminal](https://user-images.githubusercontent.com/63385587/138876771-35d37d08-d893-4394-9043-02d7cc70d8f6.png)


# License
Distributed under the MIT License. See [LICENSE](https://github.com/RajvirSingh1313/Elecrue/blob/master/LICENSE) for more information.
