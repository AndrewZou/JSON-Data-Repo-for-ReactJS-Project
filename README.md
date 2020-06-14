echo "# JSON-Data-Repo-for-ReactJS-Project" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/AndrewZou/JSON-Data-Repo-for-ReactJS-Project.git
git push -u origin master

To make this DB repo work for your local environment, please follow steps as below.

1. npm install -g jason-server

2. clone this repo to a local directory as: JSON_Server

3. CD to directory JSON_Server

4. git clone <this repo link>

//Run local JSON data server

5. json-server --watch db.json -p 3001 -d 2000

