## 1.Create github account

create [github](https://github.com/) account here

## 2.Create github Repository

click [Create Repository](https://github.com/new) to create a repository


https://github.com/23225a4502/slashmark_tuts/assets/170292118/609e7fb2-d319-494f-96f8-525d70aee2f6


## 3.Create SSH key

### To create an SSH key, follow these steps:

#### 1.Open your terminal or command prompt.

#### 2.Run the following command to generate a new SSH key:

```bash
ssh-keygen
```

example video below:-

https://github.com/23225a4502/slashmark_tuts/assets/170292118/b8698064-479e-41f0-8c19-bbf76c8ddfdf

## 4.add ssh key in github

```bash
cat ~/.ssh/id_ed25519.pub
```

#### 1.In your GitHub account settings, navigate to SSH and GPG keys > New SSH key.

#### 2.In the "Title" field, enter a descriptive name for your key (e.g., "Personal Laptop").

#### 3.Paste your public key into the "Key" field.

#### 4.Click Add SSH key.

- instruction video:-

https://github.com/23225a4502/slashmark_tuts/assets/170292118/451ae0af-534e-4e7e-9203-16302b499ca1

# Git

- 1.open terminal
- 2.check git installed or not by below command

```bash
git --version
```

![Screenshot_20240528_214811](https://github.com/23225a4502/slashmark_tuts/assets/170292118/5f6ee552-685e-440a-a822-e3684355680a)

- 3.add global configuration

```bash
git config --global user.name "USERNAME"
```
```bash
git config --global user.email "USEREMAIL"
```
- sample:-
  
![Screenshot_20240528_214919](https://github.com/23225a4502/slashmark_tuts/assets/170292118/0854f037-bd6c-4937-a98b-a628c106336e)

## 2.To download the project files from slash mark website

click [here](https://slashmark.cloud/login1.php) goto slash mark



https://github.com/23225a4502/slashmark_tuts/assets/170292118/d0d6dfd9-9bd5-4708-b4e6-b78250111c62



## 3.extract the files
## 4.push project to github repository

```bash
git init -b main
git add .
git commit -m "slash mark projects"
```
- sample video:-

https://github.com/23225a4502/slashmark_tuts/assets/170292118/d0f8f4d2-ac9e-43f3-8177-d18ff885244e


### 5.after those commands execution open the github repository and copy the line of code as shown in the **video**

- sample video:-


https://github.com/23225a4502/slashmark_tuts/assets/170292118/e6d36e9c-e23f-45c3-bdb6-2036c3d8d9bc


### 5.final command to push to github repository

```bash
git push origin main
```
- usage:-
![Screenshot_20240528_234925](https://github.com/23225a4502/slashmark_tuts/assets/170292118/e222b679-8082-4fe9-9d2d-cb74047c4204)


   

Nagendra Gubbala 😄
