

 # what is cloud
  [<img src="./../images/NEXT2020.jpg" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)

  Lets understand cloud computing models with housing analogy

- **On-Premises**: This is like building your own house from scratch, managing everything yourself.

- **IaaS**: This is like hiring a contractor to build a house to your specifications. You manage the software and data but rent the hardware.

- **Containers** as a Service: This is like renting a house and bringing your own furniture. You manage your application but not the underlying operating system.

- **PaaS**: This is like renting a furnished house. You deploy your code but the cloud provider manages everything else.

- **Function as a Service**: This is like renting a desk in a workspace. You deploy a specific function and the cloud provider manages everything else.

- **SaaS**: This is like renting a house and having someone else handle maintenance. You use the software and store your data but the provider manages everything else.

# Where should i run my stuff

 [<img src="./../images/ComputeOptions.jpg" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)

 Choosing the right infrastructure options to run your application is critical, both for the success of your application and for the team that is managing and developing it. This sketch breaks down some of the most important factors that you need to consider when deciding where you should run your stuff. Remember that no decision is necessarily final; you can always move from one option to another but it’s important to consider all the rele- vant factors. 

 # what is compute Engine
  [<img src="./../images/GCE.jpg" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)

  

Google's Compute Engine lets you create custom virtual machines (VMs) to run your applications. You can choose from pre-built VMs with set CPU and memory or create your own with the exact resources you need. This allows you to optimize your resources and costs. If your needs change, you can easily switch your VM to a different size without affecting your workload.




# What is Google Kubernetes Engine? 
  [<img src="./../images/GKE.jpg" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)


The sketch compares containers and virtual machines (VMs) for running software. VMs virtualize the entire hardware system, while containers share the host operating system's kernel. This makes containers much lighter and faster to start up than VMs. Containers improve portability, deployment speed, and reusability of applications. Notably, they help avoid the "it worked on my machine" problem by providing a consistent environment.



# What is Cloud Run? 


  [<img src="./../images/CloudRun.png" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)



Cloud Run makes deploying and running containerized applications a breeze. It takes care of everything behind the scenes, from setting up servers to automatically scaling your app based on demand. No more wrestling with complex cluster configurations or worrying about resource usage when things are quiet.

Here's what makes Cloud Run so powerful:

- Simple and Flexible: Cloud Run uses standard containers, so you can easily move your applications between Cloud Run, your own data center, or other cloud providers. No lock-in here!

- Scales Seamlessly: Cloud Run automatically adjusts the number of containers running your app based on traffic. Need more power for a sudden surge? Cloud Run scales up. Things slow down? It scales back to zero, saving you money.

- Effortless Rollouts: Test new features or updates with confidence. Cloud Run lets you split traffic between different versions of your app, so you can introduce changes gradually and monitor their impact.

- Customizable Endpoints: Use your own domain name with Cloud Run and it will even handle the security certificate for you.

- Built-in Redundancy: Cloud Run automatically ensures your application stays available, even if there are hardware failures.




# Build and Scale Your Apps Effortlessly with App Engine

  [<img src="./../images/appengine.jpg" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)



App Engine is a Google Cloud service that lets you develop and deploy applications without worrying about server management. App Engine is fully-managed serverless compute to build low latency high scalable applications. and deploy l It takes care of everything from infrastructure setup to scaling your app to meet any demand, from a handful of users to millions. 


# What is Cloud Functions? 

[<img src="./../images/cloudfunctions.png" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)



Code on Demand, No Servers Required.  Cloud Functions lets you ditch server management altogether. This event-driven service runs your code only when specific things happen, like a file upload or a database change.

## Here's what makes Cloud Functions so useful:

- Focus on Code, Not Servers: Write short, focused pieces of code (functions) to respond to events. Cloud Functions takes care of everything else, from running your code to scaling it up or down automatically.

- Events Power Everything: Cloud Functions spring to life based on events happening in your cloud environment. File uploaded? Function runs. Database updated? Function triggered!

- Easy to Move and Monitor: Built on open-source technologies, Cloud Functions is easy to migrate to other cloud platforms if needed. Plus, it integrates with Cloud Operations for clear monitoring and troubleshooting.

With Cloud Functions, you can create event-driven applications without ever having to manage a server. Just write the code, and let Google handle the rest.




# What is VMware engine? 

  [<img src="./../images/VMWareEngine.jpg" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)


Run Your VMware Workloads Seamlessly in the Cloud. Have existing VMware applications and want the benefits of the cloud?  Google Cloud VMware Engine lets you migrate your workloads to Google Cloud without needing to change a thing. It provides a fully managed service with dedicated infrastructure, keeping your environment secure and isolated.

This means:

- Modernize with Ease: Move your VMware workloads to the cloud and unlock the potential of Google Cloud services for increased agility and efficiency.

- Reduced Costs: Consolidate your infrastructure and potentially lower your total cost of ownership (TCO) by leveraging Google Cloud's resources.

- Seamless Transition: Keep using your familiar VMware tools and processes. Google Cloud VMware Engine integrates smoothly with your existing environment.

- Enhanced Security: Enjoy the peace of mind that comes with a fully isolated and dedicated infrastructure for your workloads.





# What is Bare Metal Solution? 
  [<img src="./../images/BareMetal.jpg" width=1100>](https://thecloudgirl.dev/NEXT2020.html) | [<sup>:link:</sup>](https://cloud.google.com/blog/topics/google-cloud-next/complete-list-of-announcements-from-google-cloud-next20-onair)



Moving to the Cloud, But Your Specialized Workloads Need a Lift? Many businesses are moving to the cloud for its flexibility and ease of management. But what about those critical applications with specific needs, like Oracle databases? Complex licensing, hardware requirements, and support agreements can make migrating them a challenge.

Bare Metal Solution offers a bridge to the cloud for these specialized workloads. It lets you leverage the benefits of Google Cloud  while still using your existing hardware and architecture. This translates to:

- Faster, Smoother Cloud Migration: Get your specialized applications onto the cloud without the hassle of complex adjustments. Bare Metal Solution simplifies the process.

- Modernize While Preserving Investments: Keep using your existing hardware and architecture, while still gaining access to Google Cloud's advanced features and scalability.

- Focus on What Matters: Bare Metal Solution takes care of infrastructure management, freeing you to focus on optimizing your applications.






