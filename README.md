- 👋 Hi, I’m @pavanw
- 👀 I’m interested in cloud 
- 🌱 I’m currently learning  GCP 
- 💞️ I’m looking to collaborate on DevOps
- 📫 How to reach me ...

<!---
pavanw/pavanw is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

MAIN_BRANCH=main

for k in $(git branch -r --merged $MAIN_BRANCH --format="%(refname:short)" | sed -e "s/origin\///"); do 
    if [[ $k =~ ^$MAIN_BRANCH$|^HEAD$ ]]; then
        printf "branch $k is PROTECTED\n"
    #elif (($(git log -1 --since='1 month ago' -s origin/$k|wc -l)==0)); then
	elif ; then
       echo git branch -d $k
	fi
done
