# My_project
mkdir my_project
cd my_project







if (-d .git ); the echo 'repositroy initialized'; else echo 'initialization failed'; fi
if (-f readme.md) then echo 'file created'; else echo 'file creation failed'; fi
if git log | grep -q 'initial commit'; then eco 'Commit successful'; else echo 'Commit failed'; fi
