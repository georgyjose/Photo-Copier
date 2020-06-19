# Photo Copier

I've written the code for this software to copy all the image files from my external hard disk.

  - It can recursively traverse through every folder from a given root and find copy all the image files to the specified target folder by preserving the directory structure.
  - Hashing is also implemented in the code to prevent copying of duplicate images.
  - The code can modified easily to copy all the files of required formats.
 
### To run this code,

Clone the repository
```sh
git clone https://github.com/georgyjose/Photo-Copier
```

Navigate into the project.
```sh
cd Photo-Copier/
```

To run this project, it is recommended to run it inside virtual environment. You can create a virtual environment using the following command.virtual
```sh
python3 -m venv venv
```

Activate the virtual environment by
```sh
source venv/bin/activate
```

Install the requirements
```sh
pip install -r REQUIREMENTS.txt
```

The code can be run inside Jupyter notebook. Run it using the following command.
```sh
jupyter notebook
```



License
----
**Free Software, Oh Yeah! 😜**
