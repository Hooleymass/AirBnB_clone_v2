# 0x00. AirBnB clone - The console
`Group project` | `Python` | `OOP`

#### Concepts
<em>For this project, we expect you to look at these concepts:</em>

- [Python packages](https://intranet.alxswe.com/concepts/66)
- [AirBnB clone](https://intranet.alxswe.com/concepts/74)

<p align="center">
    <img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png" alt="Airbnb">
</p>

<details>
  <summary>**Background Context**</summary> <br>

Welcome to the AirBnB clone project!

Before starting, please read the AirBnB concept page.

## First step: Write a command interpreter to manage your AirBnB objects

This is the first step towards building your first full web application: the AirBnB clone. This initial step is crucial as you will utilize what you build during this project in all subsequent projects, including HTML/CSS templating, database storage, API, and front-end integration.

Each task is interconnected and will assist you in:

- Implementing a parent class (called `BaseModel`) to handle the initialization, serialization, and deserialization of your future instances.
- Creating a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file.
- Establishing all the classes used for AirBnB (such as `User`, `State`, `City`, `Place`) that inherit from `BaseModel`.
- Developing the first abstracted storage engine for the project: File storage.
- Crafting unit tests to validate all your classes and storage engine.

## What's a command interpreter?

Do you recall the Shell? It's essentially the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

- Create a new object (e.g., a new User or a new Place).
- Retrieve an object from a file, a database, etc.
- Perform operations on objects (e.g., count, compute stats, etc.).
- Update attributes of an object.
- Destroy an object.

Now, let's dive into building our command interpreter and managing our AirBnB objects!

</details>
