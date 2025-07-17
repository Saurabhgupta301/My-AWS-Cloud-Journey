Day 1: Stepping into the Cloud — My AWS Journey Begins!

5 min read
·
Just now
![App Screenshot](https://miro.medium.com/v2/resize:fit:1100/format:webp/0*84gCnT35Q6FmY4Za.png)




Hey everyone!

As someone who’s worked in tech for about two years, I’ve really started to see how amazing and flexible “the cloud” is, especially for things like data science. So, today, I officially started my journey with AWS — that’s Amazon Web Services, a huge cloud provider!

I’m following a fantastic and super beginner-friendly series on YouTube by Prashant Kumar Paradkar. He explains things so clearly and even lets you get hands-on.

## 🔗 Links
🎥 I watched: [![AWS Cloud Tutorial]](https://youtu.be/N4sJj-SxX00?si=LIeK8pu2oCt-AdhU)

📑 I looked at:[![AWS Slide Decks — Google Drive]](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa1Rrc2dTdHFTLXRaWkd6OUJwekJvQUpTaDJEUXxBQ3Jtc0tra3otTVA0SEVvUnJQQ1MweGN6cThWN0EwRVJCR1FwazQ1cF95aFBXZ0k0Ynl4dm5EUDQwdDl3TTFaUGNvNjZacVkzR3pPLUdqQk56Z2RpUF9teDNwZW9QWFFBSDJTSVJTUi1RWEdSUS13ak1BclZfWQ&q=https%3A%2F%2Fdrive.google.com%2Fdrive%2Ffolders%2F1zuTNWyGelOiTALDZt7RF4E3uMHhcbIU7%3Fusp%3Dsharing&v=N4sJj-SxX00)


What I Figured Out Today:
🧠 Virtualization: The Magic Behind the Cloud
Imagine you have one super powerful computer. Virtualization is like a magic trick that makes this one computer act like many smaller, separate computers all at once. It creates “virtual” versions of the physical parts, like the processor, memory, and storage.

![App Screenshot](https://miro.medium.com/v2/resize:fit:1100/format:webp/0*6YnLPAnqcSvKjPYZ.jpg)

Why is this cool?

Saves Money & Space: Instead of buying lots of physical computers, you can use one big one more efficiently.
Flexible: You can easily create new virtual computers or remove old ones as you need them.
Safe: If one virtual computer has a problem, it usually doesn’t affect the others on the same physical machine.

💡 Easy Tip: Virtualization is the secret sauce that allows big companies like Amazon (AWS) to share their powerful computers with millions of users, making the cloud possible!

💻 Virtual Machines & Hypervisors: The Players
VMs (Virtual Machines): These are those “virtual computers” I just talked about. Each VM can run its own operating system (like Windows or Linux) and its own programs, completely separate from other VMs on the same physical machine. It’s like having multiple independent computers running on one piece of hardware.
Hypervisors: Think of a hypervisor as a special manager software. Its job is to control the physical computer and make sure all the VMs share its resources fairly and don’t get in each other’s way.
Type 1 Hypervisor (Bare Metal): This manager sits directly on the physical computer’s hardware. It’s super fast and efficient, which is why big cloud companies like AWS use it.
Type 2 Hypervisor (Hosted): This manager runs inside another operating system (like an app you install on your home computer). It’s simpler for personal use but not as powerful for large-scale cloud operations.

![App Screenshot](https://miro.medium.com/v2/resize:fit:1100/format:webp/0*QL46srlhlpWFNJ7s.png)

💡 Easy Tip: When you use AWS, you’re mostly dealing with VMs managed by super-efficient Type 1 Hypervisors!

☁️ What is Cloud Computing, Really?
Imagine instead of owning all your own computer servers, storage drives, and software, you could just rent them whenever you need them, paying only for what you use. That’s Cloud Computing! It’s like using electricity — you don’t build your own power plant; you just plug in and pay for the power you consume.

Different Ways to Use the Cloud (Cloud Models):

IaaS (Infrastructure as a Service): This is the most basic level. You get the raw building blocks — virtual computers (VMs), storage space, and network connections. You’re responsible for installing your operating system and software.
Example: AWS EC2 (Elastic Compute Cloud) — It’s like renting a virtual computer where you decide what to put on it.
PaaS (Platform as a Service): This is a step up. Besides the basic infrastructure, you also get a ready-to-use environment with tools, programming languages, and databases pre-set up. It’s perfect for developers because they can just focus on writing their code, not on setting up servers.
Example: For data scientists like me, AWS SageMaker is a dream! It gives us all the tools to build, train, and deploy machine learning models without worrying about the underlying servers.
SaaS (Software as a Service): This is the easiest level. You simply use a complete software application over the internet. You don’t manage anything — just log in and use it!
Examples: Gmail, Salesforce, Netflix. You just use the app, someone else handles all the tech behind it.

![App Screenshot](https://miro.medium.com/v2/resize:fit:1100/format:webp/0*nnu8vZm3Nbo7Utzn.png)

💡 Easy Tip: For data scientists, PaaS is awesome because it lets us spend more time building cool AI models and less time playing IT admin!

🌍 Why AWS? The Big Player
AWS (Amazon Web Services) is by far the biggest and most popular cloud provider out there. They offer a massive variety of services for almost anything you can imagine doing with computers.

Need a virtual computer? They have EC2.
Need somewhere to store tons of data? They have S3.
Want to analyze that data easily? They have Athena.
Want to build Machine Learning models? They have SageMaker.
And so much more!

![App Screenshot](https://miro.medium.com/v2/resize:fit:1100/format:webp/0*L9wUUFLagcqG74wE.jpg)

💡 Easy Tip: AWS has data centers all over the world. This means if your users are in different countries, AWS can serve them quickly and reliably, no matter where they are.

🧾 Setting Up My AWS Account + Free Stuff!
Today was also about getting practical! I successfully created my very own AWS account. The best part is their Free Tier — it lets you try out many services for free up to a certain limit. This is fantastic for learning without worrying about a big bill.

![App Screenshot](https://miro.medium.com/v2/resize:fit:1100/format:webp/0*LrMFpoiP7ygvvv7J.png)

💡 Easy Tip: As soon as you set up your AWS account, always, always set up billing alerts! This sends you a notification if you’re getting close to using up your free tier or spending money, so you can avoid surprises.

My Big Idea for Today:
The cloud isn’t just a place to put your old servers. It’s a whole new way to build powerful, secure, and affordable solutions. For anyone in data science, AWS is a total game-changer for handling data, training big AI models, and getting them out into the real world quickly.

I’m super excited to keep learning and share my progress every step of the way. If you’re also diving into AWS, moving into tech, or just exploring the cloud for data, let’s connect and learn together! 🌱

You can find me here:

LinkedIn: https://www.linkedin.com/in/saurabhgupta301/

GitHub: https://github.com/Saurabhgupta301/Saurabhgupta301

Hashnode: https://hashnode.com/@saurabhgupta

#AWS #CloudComputing #LearningInPublic #DataScience #100DaysOfCloud #Virtualization #CloudJourney #AWSForBeginners #CareerTransition #SageMaker #MLOnCloud #AWSLearning #PrashantKumarParadkar

#Cloud Computing
#AWS
#Data Science
#Data Engineering
#Machine Learning Ai
