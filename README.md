- 👋 Hi, I’m @pavanw
- 👀 I’m interested in cloud 
- 🌱 I’m currently learning  GCP 
- 💞️ I’m looking to collaborate on DevOps
- 📫 How to reach me ...


aws ec2 describe-images --owners 309956199498 --filters 'Name=name,Values=RHEL-7.9_HVM_GA*' 'Name=state,Values=available' --query 'reverse(sort_by(Images, &CreationDate))[:1].ImageId'
<!---
pavanw/pavanw is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
