# Workshop Developer Experience and User Personas

The Developer Experience Workshop focuses on user-centered design in platform engineering. It introduces the concept of
Platform Teams that support Stream-Aligned Teams, aiming to reduce the cognitive load of developing and maintaining
applications, and highlights the importance of understanding developers' needs for efficient platform creation. The
workshop emphasizes good Developer Experience (DX) characterized by clear documentation, intuitive API design, precise
error messages, and efficient tools, alongside the use of User Personas to represent typical user characteristics,
needs, and behaviors, providing a shared understanding and empathy towards users.

## Table of Contents

## User Persona Portraits and Sample Features

Contained in the folder workshop-resource are sample portraits of User Personas and a list of features that can be
used to make creation of User Personas less time-consuming. I recommend using these in conjunction with real
user research to create User Personas for your own platform. Start by discussing possible User groups and then
split into groups of 2-3 people to create User Personas for each group. Afterwards, present your User Personas to
the other groups and discuss similarities and differences.

## Getting Started with MARP

These instructions will get you a copy of the project up and running on your local machine for development and testing
purposes.

### Prerequisites

You will need to have the following tools installed on your machine.

1. Node.js and npm
    - Visit the [official page](https://nodejs.org/en/download/) to download and install Node.js and npm

2. Git
    - Visit the [official page](https://git-scm.com/downloads) to download and install Git

3. Visual Studio Code (VS Code)
    - Visit the [official page](https://code.visualstudio.com/download) to download and install Visual Studio Code

### Installing

Follow these steps to get the project running:

1. Clone the repository to your local machine
    ```
    git clone https://gitlab.rewe.local/gitops/poc/architekturentschiedung-fuer-neue-kubernetes-plattform.git
    ```
2. Navigate into the project directory
    ```
    cd architekturentschiedung-fuer-neue-kubernetes-plattform
    ```
3. Install MARP CLI globally
    ```
    npm install -g @marp-team/marp-cli
    ```
   Alternatively install MARP CLI using brew
    ```
    brew install marp-cli
    ```

4. Install the Marp for VS Code extension:
    - Open VS Code
    - Go to the Extensions view (⇧⌘X)
    - Search for `marp` and install Marp for VS Code

## Running the Presentation

Once you have the project up and running, you can render the markdown file to a slideshow by running:

```
marp kubernetes-platformen.md
```

This command will create a `kubernetes-platformen.html` file that you can open in a web browser to view the slideshow.
