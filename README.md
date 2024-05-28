## 1.Create github account

create [github](https://github.com/) account here

## 2.Create github Repository

click [Create Repository](https://github.com/new) to create a repository

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


## 5.To download the project files from slash mark website

click [here](https://slashmark.cloud/login1.php) goto slash mark

## 6.extract the files

## 7.push project to github repository

```bash
git init -b main
git add .
git commit -m "slash mark projects"
```

### 8.after those commands execution open the github repository and copy the line of code as shown in the **video**

[video]()

### 9.final command to push to github repository

```bash
git push origin main
```

Nagendra Gubbala 😄
