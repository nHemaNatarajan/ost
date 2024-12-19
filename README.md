mvn archetype:generate -DgroupId=com.example -DartifactId=my-amp -DarchetypeArtifactId=maven-arc
hetype-quickstart -DinteractiveMode=false
cd my-app
git init
echo "target/">.gitignore
echo ".idea/">>.gitignore
echo ".iml/">>.gitignore
git add .
git commit -m"initial"
git remote add origin  https://github.com/nHemaNatarajan/ost.git
git push -u origin master
git status

