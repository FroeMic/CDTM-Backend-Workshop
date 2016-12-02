# CDTM-Backend-Workshop

For many the term 'Backend-Development' is synonymous to a big black box. The goal of this workshop to shed light on said black box and convey a basics set of shared vocabulary and understanding around the field of Backend-Development for people with limited programming experience.

This workshop combines theoretical input lessons with practical programming exercises to build a solid understanding of the taught content. During the course the students will be guided through developing a backend application for a 'Todo-Application'.

## Workshop Structure

In order to make the content of this workshop easily accessible to you we put most of it straight into the Wiki of this repository. Additionally we will gradually publish slides with additional input.

### Repository Structure

The repository structure will look as follows. Please note that there are certain guideline to follow, in order to avoid problems throughout the workshop.

1. Only modify files which are inside the `/src` folder
2. Do not modify anything within the `/src/server/static` folder

```
.
+-- README.md
+-- slides/                         (lecture slides)
+-- src/                            (YOUR CODE)
|   +-- exercises/                  (single exercises will go here)
    |   +-- exerciseXYZ/            
    |   +-- .../            
|   +-- server/                     (your server implementation)
    |   +-- server.py               
    |   +-- static/                 (frontend -> don't modify)  
    |   +-- ...
+-- solutions/                      (solutions will be publish here)
|   +-- server/                     (solutions for each step of the server)
    |   +-- server-01-description   
    |   +-- ...
```

We will explain more in time. Happy coding :-)
