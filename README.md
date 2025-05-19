# MONGODB PRATICE

## Query / Find Documents

### 1. get all documents

![image](https://github.com/user-attachments/assets/83444875-1dc0-42c0-ac38-6450b500c086)

### 2. get all documents with `writer` set to "Quentin Tarantino"

![image](https://github.com/user-attachments/assets/9fa4f36c-5de3-4321-a3d7-c3fe3a40390f)

### 3. get all documents where `actors` include "Brad Pitt"

![image](https://github.com/user-attachments/assets/f4daf48c-a22c-43d4-8e1e-5f64b43033fb)

### 4. get all documents with `franchise` set to &quot;The Hobbit&quot;

![image](https://github.com/user-attachments/assets/5b08f576-c067-49ca-8432-3879247f33fe)

### 5. get all movies released in the 90s

![image](https://github.com/user-attachments/assets/257386b1-cfc1-4f83-bd8a-13b9158c0f67)

### 6. get all movies released before the year 2000 or after 2010

![image](https://github.com/user-attachments/assets/fa0a9c5c-6044-4140-970e-c5294aeebb0a)



## Update Documents

 1. add a synopsis to &quot;The Hobbit: An Unexpected Journey&quot; : &quot;A reluctant hobbit, Bilbo Baggins,
sets out to the Lonely Mountain with a spirited group of dwarves to reclaim their mountain home - and the gold within it - from the dragon Smaug.&quot;

BEFORE UPDATE
![image](https://github.com/user-attachments/assets/81e03f35-5c7a-40ac-ba94-f57bf9796c5a)

AFTER UPDATE
![image](https://github.com/user-attachments/assets/313c1eb7-e7c1-4dcf-a208-81ae47894286)


2.add a synopsis to &quot;The Hobbit: The Desolation of Smaug&quot; : &quot;The dwarves, along with Bilbo
Baggins and Gandalf the Grey, continue their quest to reclaim Erebor, their

BEFORE UPDATE
![image](https://github.com/user-attachments/assets/13412952-3fb1-4bb2-90d6-8319d048d530)

AFTER UPDATE
![image](https://github.com/user-attachments/assets/f18e5821-1508-4a8f-a573-775962216f2d)


3.add an actor named &quot;Samuel L. Jackson&quot; to the movie &quot;Pulp Fiction&quot;

BEFORE UPDATE

![image](https://github.com/user-attachments/assets/6fbf5001-ab01-4451-954e-caf691a02475)

AFTER UPDATE

![image](https://github.com/user-attachments/assets/31a40a4f-2c30-4575-9cea-ae2282285350)



## Text Search

### 1.find all movies that have a synopsis that contains the word &quot;Bilbo&quot;
![image](https://github.com/user-attachments/assets/ecfb450a-a072-4732-a089-3930a3234e0a)

### 2.find all movies that have a synopsis that contains the word &quot;Gandalf&quot;
![image](https://github.com/user-attachments/assets/fe6e996b-92f4-40d1-bbf0-f870a89886e7)

### 3. find all movies that have a synopsis that contains the word &quot;Bilbo&quot; and not the word &quot;Gandalf&quot;
![image](https://github.com/user-attachments/assets/61fa2f17-b40a-40bc-8253-9da70abb3e31)

### 4. find all movies that have a synopsis that contains the word &quot;dwarves&quot; or &quot;hobbit&quot;
![image](https://github.com/user-attachments/assets/3fb8535e-7bf4-442c-8ffb-3a0d201a8ec4)

### 5. find all movies that have a synopsis that contains the word &quot;gold&quot; and &quot;dragon&quot;
![image](https://github.com/user-attachments/assets/ec7c1b61-a4f2-4fc3-a6e8-348b104ffc49)


## Delete Documents

### 1. delete the movie &quot;Pee Wee Herman&#39;s Big Adventure&quot;
![image](https://github.com/user-attachments/assets/fcc5237b-b7cd-42fd-a1a4-373451d1936c)

### 2. delete the movie &quot;Avatar&quot;
![image](https://github.com/user-attachments/assets/01376bd9-4df0-4c3b-b69f-ce11bde10182)


## Relationships

### 1. Insert the following documents into a `users` collection
![image](https://github.com/user-attachments/assets/51f3fda4-956c-4dcc-a0c3-95489da891d9)

After result:

![image](https://github.com/user-attachments/assets/fb4313b0-c31c-4484-9fbd-ffc8809a0cad)


### 2. Insert the following documents into a `posts` collection
![image](https://github.com/user-attachments/assets/cdc9be0b-468b-437f-a25c-053faed197ee)
![image](https://github.com/user-attachments/assets/97ba1f64-ab3f-4518-8388-90021ee5a103)

### 3. Insert the following documents into a `comments` collection
![image](https://github.com/user-attachments/assets/e4cf6e10-3342-412e-908e-b3825d64b437)
![image](https://github.com/user-attachments/assets/a0455237-5caa-4d81-8dd4-0db26fa16132)

Relational Afterwards:

![image](https://github.com/user-attachments/assets/bfe9a1cd-cb73-4c04-a710-f0f1f6ad4874)


## Querying related collections

### 1. find all users
![image](https://github.com/user-attachments/assets/e1b26449-f9ca-4f80-803f-ebb4b29227d2)

### 2. find all posts
![image](https://github.com/user-attachments/assets/988e2972-588f-4bf3-a2b4-a16995e62252)

### 3. find all posts that was authored by "GoodGuyGreg"
![image](https://github.com/user-attachments/assets/4278c1ca-ae3c-42db-b387-0de11fa0e4fc)

### 4. find all posts that was authored by "ScumbagSteve"
![image](https://github.com/user-attachments/assets/84dfeec3-b799-40dc-9a03-7f2faffeae63)

### 5. find all comments
![image](https://github.com/user-attachments/assets/54f942c3-2440-4a9c-b156-bbaaa9b6dc9c)

### 6. find all comments that was authored by "GoodGuyGreg"
![image](https://github.com/user-attachments/assets/94fbfbf1-5c36-42ef-b977-4a81181f9be4)

### 7. find all comments that was authored by "ScumbagSteve"
![image](https://github.com/user-attachments/assets/c9ef3b12-cd1d-4d52-826b-21d67403caae)

### 8. find all comments belonging to the post "Reports a bug in your code"
![image](https://github.com/user-attachments/assets/788a5f4b-6f7f-4ff1-a67a-2ca32e3ff623)






























