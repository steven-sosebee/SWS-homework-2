# UNC Coding Boot Camp Week 2 Homework

## Assignement Crieria

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

### Technical Acceptance Criteria: 40%

[x] Satisfies all of the above acceptance criteria.

### Deployment: 32%

[x] Application deployed at live URL.

[x] Application loads with no errors.

[x] Application GitHub URL submitted.

[x] GitHub repository contains application code.

### Application Quality: 15%

[x] Application resembles the mock-up functionality provided in the homework instructions.

### Repository Quality: 13%

[x] Repository has a unique name.

[x] Repository follows best practices for file structure and naming conventions.

[x] Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

[x] Repository contains multiple descriptive commit messages.

[x] Repository contains quality readme with description, screenshot, link to deployed application.


## Examples of code used to meet criteria:

Media screen query was used to create a mobile-first design.  Then as the viewport expands past 768px, the layout changes to allow for more functionality.

```

/* Pseudo elements create the blur effect for projects not highlighted. */
article::before{
    content: "";
    position: absolute;
    filter:blur(10px);
    padding: 0px;
    margin: 0px;
    left: -25px;
    right: -25px;
    top: -25px; 
    bottom: -25px;
    background:inherit;
    box-shadow: inset 0 0 0 300px rgba(161, 162, 163, 0.3);
    
}
```


```

/* Pseudo states create animations when hovering over elements. */
article:hover{
    transform: scale(1.02);
    z-index: 1;
}
```

```

/* Begin larger screen styles and responsive layouts */
@media screen and (min-width:768px) {
```

## Preview of working application:
![Preview](./assets/images/preview.gif)
