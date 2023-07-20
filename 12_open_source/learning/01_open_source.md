<style>
p, li {
  max-width: 992px;
}
pre {
  max-width: 992px;
}
h1 {
  font-size: 3rem;
}
h2 {
  font-size: 2.6rem;
}
h3 {
  font-size: 2.2rem;
}
h4 {
  font-size: 1.8rem;
}
h5 {
  font-size: 1.6rem;
}
</style>   

# **Open Source Python Libraries and Installation with pip**

Python, a general-purpose programming language, offers a wealth of open source
libraries and modules that aid developers in solving complex problems
efficiently. These libraries cover a wide range of applications, from web
development and data analysis to artificial intelligence and scientific
computing. 

The Python Package Index, or PyPI, is a vast repository of open-source software
for Python. It is a platform where developers can share and collaborate on
Python code. You can install these packages directly using Python's package
manager, `pip`.

## **Understanding Open Source Software**

Open source refers to a type of software whose source code is released under a license that grants users the freedom to read, modify, and distribute the software. This is in contrast to proprietary software, where the software is under copyright, and users are generally not allowed to view or modify the source code.

The idea behind open source is not just about access to the source code. The
Open Source Initiative, a global non-profit organization dedicated to promoting
open source, describes open source software as being about collaboration,
transparency, and community-oriented development. Here are a few key points that
define open source software:

1. **Free Distribution:** The software can be freely distributed. Anyone can
   give away or sell open source software, provided they comply with the license
   terms. 

2. **Source Code Availability:** The source code of the software is available
   for anyone to view, use, modify, and distribute. 

3. **Derived Works:** The license allows modifications and derived works, and it
   allows them to be distributed under the same terms as the license of the
   original software. 

4. **Integrity of The Author's Source Code:** While the license may allow code
   modifications, it may also require them to be documented or even to be
   submitted back to the community, allowing everyone to benefit. 

Open source software has several advantages. It promotes collaboration, as
developers from around the world can work together to improve the code. It
allows for rapid bug detection and fixes. Open source projects can also serve as
a learning resource for new developers, as they can study the source code to
learn how the software works. 

Python, the language we're discussing in this tutorial, is itself an example of
open source software. This means that its source code is freely available, and
anyone can contribute to its development. 

Well-known examples of open source projects include the Linux operating system,
t,he Apache web server, and the Firefox web browser. Many Python libraries, like
`pygame` we're discussing in this tutorial, are also open source, allowing for
community-driven improvement and enhancement.

## **GitHub and Open Source Software**

GitHub is a popular web-based hosting service for version control and source
code management. It is built on Git, a distributed version control system
developed by Linus Torvalds. GitHub is widely used by programmers for
collaboration on projects, and it's home to millions of open source projects. 

When it comes to open source projects, GitHub provides a platform where
developers can share code, collaborate on development, track issues, and manage
changes to the code. It makes contributing to open source projects more
accessible and organized, thanks to features like pull requests, which allow
anyone to suggest changes that can then be reviewed and potentially merged into
the project. 

### **Evaluating the Health of an Open Source Project**

<img
src="https://raw.githubusercontent.com/HWilliams64/summer_python_12_week/main/12_open_source/img/pygame-git.png"
alt="Pygame's Github repository" width="100%"/>

*This is an image of Pygame's Github repository. The numbers are referenced in the list below*

There are several ways to evaluate the health and activity of an open source
project on GitHub: 

1. **Stars:** The number of stars a project has received from users is a good
   indicator of its popularity. However, it's important to note that a high
   number of stars doesn't necessarily mean high quality or active maintenance.
   Generally:
    - \>700 stars is considered well-known
    - \>5K stars is considered popular
    - \>10K stars is considered very popular
    - \>30k stars is considered industry standard

2. **Forks:** The number of forks indicates how many people found the project
   interesting or useful enough to create their own version. A high number of
   forks often indicates a highly influential project. 

3. **Commit Activity:** By looking at the commit history, you can see the
   activity over time. Regular commits signify active development and
   maintenance. On the other hand, a project with no recent commits may be
   inactive or abandoned. 

4. **Contributors:** The number of contributors shows how many people have
   contributed to the project. A project with many contributors usually
   signifies a healthy, collaborative project. However, do also consider the
   balance between the core contributors and the wider community, as projects
   can also suffer from too few maintainers relative to the size of the user
   community. 

5. **Issues and Pull Requests:** Open, unaddressed issues or pull requests might
   be a sign of an unmaintained project. Look at how issues and pull requests
   are handled - are they addressed promptly and effectively? 
   
6. **Users:** This feature on GitHub shows the number of other repositories
   using a project. If a project is being used by many other repositories, it's
   a good sign that it's reliable and well-maintained. This can be especially
   useful for libraries or packages, as it indicates the breadth of the
   project's adoption in other software. Be aware, though, that this number will
   also include forks of the repository, which are not necessarily using the
   project in the way intended. 

7. **Documentation:** Good open source projects have up-to-date documentation,
   which shows the project maintainers are interested in helping newcomers
   understand the project. 

Remember, these are not hard-and-fast rules, but they can give you a sense of a
project's health and whether it's being actively maintained. Evaluating open
source projects on these factors can help you make an informed decision about
whether to use or contribute to a project. 


## Getting Started

### **Prerequisites:**

1. Python 3.x installed: Many Python libraries require a 3.x version of Python, though the specific version needed may vary depending on the package. Ensure you have the appropriate version installed.
2. pip: This is the standard package manager for Python, allowing you to install and manage additional packages not included in the Python standard library. It is included by default if you have Python version 3.4 or later.

In this tutorial, we'll walk through the process of finding a library on PyPI, understanding its documentation, and installing it using pip. To illustrate, we'll use `pygame`, a popular Python library for creating video games.

### **Step 1: Find a Library on PyPI**

Navigate to the Python Package Index website at https://pypi.org/. Here you can search for the `pygame` library, or any other library you wish to install. Once you've located the library, click on it to view more information such as the library's documentation and installation instructions.

### **Step 2: Understanding the Documentation**

The documentation of a library is a vital resource to understand how to use it. The PyPI page for the library typically provides a brief overview and links to more detailed documentation.

The `pygame` library documentation, for example, provides a getting-started guide, tutorials, and an API reference. Before using the library, familiarize yourself with at least the basic usage instructions.

### **Step 3: Install the Library with pip**

Once you have a basic understanding of the library, it's time to install it.
Open your terminal

   1. **Using the Command Palette:**

      - You can open the Command Palette with `Ctrl+Shift+P` (Windows/Linux) or
        `Cmd+Shift+P` (MacOS), then type "Terminal: New Terminal" and hit `Enter`. 

   2. **Using a Keyboard Shortcut:**

      - You can also open the terminal using a shortcut. By default, this is ``
        Ctrl+` `` (Windows/Linux) or `` Cmd+` `` (MacOS). 

Now that the terminal is open type the following command:

```bash
pip install pygame
```

Here, `pip install` is the command that instructs pip to install a package, and `pygame` is the name of the package we want to install. Upon pressing Enter, pip will download and install the `pygame` library (along with any of its dependencies) from PyPI.

### **Step 4: Verify the Installation**

After the installation, you should verify if the library has been correctly installed. In your terminal, start the Python interpreter by typing `python`. Then, attempt to import the `pygame` library:

```python
import pygame
```

If you don't see any error message after running this command, congratulations! You have successfully installed and verified a Python open-source library.

**Note:** If you're working in a Grader Than Workspace, your Python environment is already set up. If you have multiple Python environments on your machine, ensure that you install the package in the correct environment by specifying the path to the Python interpreter of the desired environment. For example:

```bash
/path_to_your_environment/bin/python -m pip install pygame
```

### **Step 5: Usage**

With the library installed, you can now use it in your Python programs. Here's a
simple example of using the `pygame` library to create a window for a game. Copy
and paste the code below into a python .py file in your workspace:

```python
import pygame
pygame.init()

# Set the size of the window
size = (700, 500)
screen = pygame.display.set_mode(size)

# Set the title of the window
pygame.display.set_caption("My First Game")

# Loop until the user clicks the close button.
done = False
clock = pygame.time.Clock()

while not done:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            done = True

    # Fill the screen with a white background
    screen.fill((255, 255, 255))
    
    # Update the screen
    pygame.display.flip()

    # Limit frames per second
    clock.tick(60)

# Close the window and quit.
pygame.quit()
```

In this script, we import the `pygame` library, initialize it with `pygame.init()`, create a window with a certain size, and set its title. We then enter a loop where we wait for the user to close the window.

Remember that the exact usage will depend on the library you are using, and you should always refer to the library's documentation for correct usage instructions.

This tutorial should have equipped you with the knowledge to find, install, and begin using open source Python libraries. Happy coding!