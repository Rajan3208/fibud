
Approach:

Okay, I create the simple UI where real expert of fibud present you can see in the web app which is written in flutter and then converted into javascript using flutter build web.

To facilitate seamless interaction between users and fitness experts, I developed a custom API that securely manages expert credentials and information. When an expert logs in using the POST method, their details are authenticated and stored in the system. Similarly, when users request expert information, the API retrieves relevant data using the GET method.

All expert and user data is securely stored on Google Cloud, ensuring scalability, reliability, and quick access. The API is designed with security best practices, including authentication and authorization mechanisms, to protect sensitive user and expert information.

The API also allows easy integration with the platform’s front end, enabling users to explore expert profiles, qualifications, and available workout plans effortlessly.

By leveraging Google Cloud services, the system ensures efficient data retrieval and storage, minimizing latency and providing a smooth user experience.

# First, I build Flutter web app using this command
flutter build web

# Create a new branch 'gh-pages' in my repository
cd build/web

git init

git add .

git commit -m "Web deployment"

git branch -M main

git remote add origin https://github.com/Rajan3208/fibud

git push -u origin main:gh-pages -f
