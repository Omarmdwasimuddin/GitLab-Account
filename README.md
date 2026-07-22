## heading...

#### Visit---> https://gitlab.com/ --->Click: Sign in ---> Google or Github account diye verification and account create koro.
![](https://imgur.com/6nbIqjP.png)

---

#### Click: Create blank project --->Project name daw--->Click: Create project
![](https://imgur.com/X0xwhXY.png)

---

#### Click: New file 
![](https://imgur.com/CWNyc9G.png)

---

#### File name daw: .gitlab-ci.yml ---> code daw and click koro: Commit changes--->Commit message daw: Add new file---> and Commit changes abar click koro.
![](https://imgur.com/kOrpPPA.png)
```bash
stages: 
    - "my stage 1"
    - "my build stage"
    - "my test stage"



MY Job:
    stage: "my stage 1" 
    script: 
        - |
            echo "My job from stage 1"



MY build Job:
    stage: "my build stage" 
    script: 
        - |
            echo "My job from stage build"



MY test Job:
    stage: "my test stage" 
    script: 
        - |
            echo "My job from stage test"
```
---

#### Click---> Status: failed
![](https://imgur.com/qnxw0mh.png)
