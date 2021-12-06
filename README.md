# Tech

**Mongo**

https://stackoverflow.com/questions/64664740/node-js-mongoose-find-method-usage-with-key-value-in-object
https://mongoplayground.net/

[#1 Mongoose - deep collections connect with populate](https://youtu.be/c2oWH1g2Fng)

[(populate)app.js](https://gist.github.com/goish135/5721bfadb0e6946abcd6eef2b86113e0)

**Topic Sharing**

https://hackmd.io/@goish135/TS_Anthos


**Next.js**

https://nextjs.org/learn/basics/create-nextjs-app

Project ... practice


[Build Tic Tac Toe with React](https://www.youtube.com/watch?v=mM-Se5TEmX8)

- [HackMD - React](https://hackmd.io/@goish135/rJBHkoltt)

---

https://zh-hant.reactjs.org/tutorial/tutorial.html

- [Issue with babel-jest dependency when running npm start in a React app](https://stackoverflow.com/questions/53089122/issue-with-babel-jest-dependency-when-running-npm-start-in-a-react-app)

    > rm -rf ~/node_modules/babel-jest ~/node_modules/jest

- [npm start error with create-react-app](https://stackoverflow.com/questions/39959900/npm-start-error-with-create-react-app)



Functional Programming:

https://zims-en.kiwix.campusafrica.gos.orange.com/wikibooks_en_all_maxi/A/C_Programming/Side_effects_and_sequence_points

**[MERN Backend]**

1. **[GET/POST/`PUT/DELETE`]**
2. TDD 
    - Use case:  getById 
    - Test: JEST 
    - npm run test (**defined** by package.json)

DIY: https://hackmd.io/@goish135/backend-practice

ref: https://yubintw.github.io/MERN-backend-create/export/#/

---

**[Git Pull Request]**

ref: https://backlog.com/git-tutorial/tw/stepup/stepup2_1.html

**Extension**

    1. Git Lens
   
    2. *Git Graph

1. 情境1 : 建 master(main)， branch(feature/a)， **merge** branch into master

    > 待修正
    - git init 
    - git branch master
    - add a.txt file 
    - git add . 
    - git commit -m "a.txt"
    - git branch feature/a
    - git chechout feature/a
    - add b.txt file
    - git add .
    - git commit -m "b.txt"
    - git chechout master
    - git mearge feature/a
3. 情境2 : 解決**衝突**，dev merge 到 master 會有衝突(選A?,選B?,選Both?)
    
    > 待修正
    
    - git clone xxx 
    - git branch  # 查看分支 # 找不到除了master以外的分支
    - git branch -a # 長出來了(master以外的分支)
    - git checkout [某分支]
    - git branch 
    - git checkout master
    - git merge dev # 衝突發生
    - 編輯 >>> <<<< (選A?,選B?,選Both?) 
    - git add .
    - git commit -m "ex:Both"
    - git merge dev

---

ref: **[助教Resource]**

1. Backend :thumbsup:
    - https://yubintw.github.io/MERN_Backend_TDD_slide/export/index.html#/
3. Frontend
    - https://github.com/xiao617/React_slide
    - https://github.com/xiao617/React_practice_breakdown
    
    - https://primefaces.org/primereact/showcase/#/
    - https://zh-hant.reactjs.org/docs/hooks-intro.html
    - 補充: JS - for foreach map & reduce 

> PS: Cool `reveal.js`

---

**Rest API Spec.**

[Swagger Editer](https://editor.swagger.io/?fbclid=IwAR06t_6b3-D66muBIynQlsypzIZTcgVpBzTDa1g9a19O3ntzKLurecoAVKM)

[OpenAPI 3.0 Tutorial](https://support.smartbear.com/swaggerhub/docs/tutorials/openapi-3-tutorial.html)

---

- MERN frontend
  - call backend?   

- MERN Overview 
- TypeScript & TDD

# env

[What is the difference between SETX and SET in environment variables in Windows](https://superuser.com/questions/916649/what-is-the-difference-between-setx-and-set-in-environment-variables-in-windows)

---

**[預習 Prep]**

[30天精通Git版本控管](https://ithelp.ithome.com.tw/users/20004901/ironman/525)

---

https://hackmd.io/@goish135/工作內容

https://hackmd.io/@goish135/自我介紹

https://hackmd.io/@goish135/面試
