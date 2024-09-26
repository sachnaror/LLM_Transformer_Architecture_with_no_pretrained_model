# Welcome to the LLM Transformer Project!



├── LLM_Transformer_Architecture_with_no_pretrained_model/
│   ├── requirements.txt
│   ├── README.md
│   ├── .env
│   ├── manage.py
│   ├── vector_database/
│   │   ├── milvus_index.bin
│   │   ├── faiss_index.bin
│   │   └── db_config.py
│   ├── llm_app/
│   │   ├── urls.py
│   │   └── views.py
│   │   ├── models/
│   │   │   └── embedding_model.py
│   │   └── static/
│   │   ├── api/
│   │   │   ├── serializers.py
│   │   │   ├── urls.py
│   │   │   └── views.py
│   │   └── templates/
│   ├── scripts/
│   │   ├── generate_embeddings.py
│   │   ├── load_faiss_index.py
│   │   ├── train_custom_model.py
│   │   └── optimize_faiss_index.py
│   ├── data/
│   │   └── raw_text/
│   │   └── processed_text/
│   │   └── embedding_vectors/


## What is this project?

This project is like a magic box that helps us understand and create cool things with words! It uses something called a **Transformer**, which is a special kind of computer brain that can learn from a lot of information.

### Why is it special?

- **No Pre-trained Models**: This means we are teaching the computer from scratch, like learning to ride a bike without training wheels!
- **Fun with Words**: We can make new sentences, understand stories, and do lots of exciting things with language!

---

## What's inside the box?

Here’s what you’ll find in our project:

### 1. Important Files

- **requirements.txt**: This is like a shopping list. It tells us what special tools (or packages) we need to make our project work.
- **README.md**: You are reading this! It helps you understand what our project is and how to use it.
- **.env**: This is a secret box where we keep our important keys and codes safe.
- **manage.py**: This is like our magic wand. It helps us control the project and make things happen!

### 2. Special Folders

- **vector_database/**:
  - **milvus_index.bin**: This file helps us remember things.
  - **faiss_index.bin**: Another helper for remembering!
  - **db_config.py**: This file tells us how to connect to our memory helpers.

- **llm_app/**: This is where the magic happens!
  - **urls.py**: This tells us where to go when we want to see something special.
  - **views.py**: This shows us what we can see on the screen.
  - **models/**:
    - **embedding_model.py**: This is like a brain that helps us understand words better.
  - **static/**: This is a place for our pictures and styles.
  - **templates/**: This is where we keep our designs for how things look.
  - **api/**: This helps us talk to other cool projects!
    - **serializers.py**: This makes sure we understand each other.
    - **urls.py**: This is another map to guide us.
    - **views.py**: This shows us what we can see here too!

- **scripts/**:
  - **generate_embeddings.py**: This helps us create our word magic!
  - **load_faiss_index.py**: This helps us find our memories.
  - **train_custom_model.py**: This teaches our computer how to learn.
  - **optimize_faiss_index.py**: This makes our memory helpers work even better!

- **data/**: This is where we keep our special information.
  - **raw_text/**: This is where we keep our original stories.
  - **processed_text/**: This is where we keep our stories after we’ve worked on them.
  - **embedding_vectors/**: This is where we keep our magic number helpers for words!

---

## How to Play with the Project

1. **Get Ready**: First, make sure you have Python installed on your computer. Python is a friendly tool that helps us run our project.

2. **Install Requirements**: Open your terminal (it’s like a magic command center) and type this:

```
pip install -r requirements.txt

```

This will gather all the special tools we need!



3. **Run the Project**: To start our magic, type:

```
python manage.py runserver

```

Now you can see the project in your web browser!

---

## Need Help?

If you have any questions or need help, feel free to ask!

---



```
