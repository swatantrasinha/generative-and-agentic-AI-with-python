# Section 02

## Virtual Environment

This is mainly for safeguarding application from other versions.

<details>
  <summary>Steps to create Virtual Environment</summary>
  <p>

1. create folder say - "virtual-env"

2. inside "virtual-env", create one more folder "src"

3. inside terminal - go to this "virtual-env" location : 
   
   a) verify python is there
    > python3 --version

   b) give below command to create virtual env with name ".venv" (name can be anything) :  

   > python3 -m venv .venv

   c) to activate 

   > source .venv/bin/activate

   this will take the terminnal to virtual env

   d) create a new file "requirements.txt" inside folder "virtual-env" parallel to ".venv" and "src"

   e) write some library name in requirements .txt :

   f) install the librarries in the "requirements.txt" to the virtual env

    > pip install -r requirements.txt

<img width="666" height="176" alt="image" src="https://github.com/user-attachments/assets/5ac56f63-2ead-406b-85a0-7d5eafb1c895" />


   

   g) give command "deactivate" to get out of virtual env

   4. we can include ".venv" to ".gitignore" file

   </p>
</details>




---

## Organize Python Code

<img width="654" height="423" alt="image" src="https://github.com/user-attachments/assets/4cec7a94-c401-4d5b-92e9-a5c2d5183fa4" />

---


