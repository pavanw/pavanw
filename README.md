- 👋 Hi, I’m @pavanw
- 👀 I’m interested in cloud 
- 🌱 I’m currently learning  GCP 
- 💞️ I’m looking to collaborate on DevOps
- 📫 How to reach me ...

<!---
pavanw/pavanw is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/*
import logging
import argparse
import re
import sys
import smtplib, ssl

logger=logging.getLogger()
logger.setLevel(logging.INFO)
logging.basicConfig(format='%(message)s')

global args

def main(_agrs):
    global args
    parser = argparse.ArgumentParser()
    parser.add_argument('--author',type=str,required=True)
    parser.add_argument('--branch',type=str,required=True)
    args = parser.parse_args(_agrs)

    email=args.author
    email=(re.split(': |, |\<|,|\>|\n',email))
    print(email[2])
    
    if args.branch:
       print(f"you have entered branch as  {args.branch}")
    else:
        print("none")


if __name__ == "__main__":
    main(sys.argv[1:])

/*
