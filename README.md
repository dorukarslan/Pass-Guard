# Pass-Guard
<p align="left">
  <img src="https://github.com/dorukarslan/Pass-Guard/assets/79598598/09b6befe-fa42-49f0-b609-f8de5fa3b9c0" alt="Pass-Guard Logo" width="300" height="300">
</p>

### You can visit the link below to see the demo video
https://youtu.be/NbM7geXi5kM

## Project Overview

The Pass Guard project leverages advanced technologies to present a robust alternative to physical cards often used in institutions. Its aim is to offer a more sustainable, easier-to-use option that eliminates the need for carrying around physical cards.

The system relies on face scanning technology for user verification, analyzing the user in real-time during every transaction and comparing this with the user's details already stored in the database. As an added layer of convenience and flexibility, the system supports QR code scanning for performing transactions within the institution, a viable alternative to NFC technology.

A unique feature of Pass Guard is its implementation of a blockchain-based solution, allowing users to transfer money both interpersonally and to in-house shops. These transactions are recorded on a secure, transparent, and decentralized ledger, ensuring the integrity and traceability of every transaction.

To ensure robustness and scalability, Pass-Guard's architecture is built on a foundation of state-of-the-art technologies. The mobile front-end development is based on the Flutter framework, providing a visually appealing and intuitive user interface. The back-end utilizes the Python FastAPI framework for reliable data processing, while the admin interface is powered by the Golang Fiber framework for efficient system management.

Pass-Guard leverages MongoDB as its database system, enabling efficient storage and retrieval of user data. MongoDB's flexible and scalable nature aligns seamlessly with Pass-Guard's requirements, enhancing the overall performance and responsiveness of the application.

## Winner of the "Young Brains New Ideas" Graduation Projects Competition
We are proud to announce that Pass-Guard has secured the first place in the prestigious "Young Brains New Ideas" graduation projects competition organized by the Informatics Association of Turkey (TBD)! This recognition is a testament to our team's hard work and dedication in developing Pass-Guard as a sustainable and secure alternative to traditional physical cards used in various institutions.



## System Functions

Upon successful user registration and administrative approval, the application initiates a face verification process during login. The user's real-time face snapshot is captured and compared to the faces stored in the database. If the verification is successful, a JWT token is generated and returned, granting access to a secure home screen. This screen displays the user's virtual card information, account balances, and recent actions.

For every transaction, the app triggers a face scan to confirm the user's identity, ensuring a high level of security. Depending on the user's phone opeation, the system supports NFC or QR code functionality for performing transactions.

Simultaneously, administrators and security personnel can monitor all activity logs from the admin frontend, upholding system integrity and enabling prompt responses to any suspicious activities.

![docker](https://github.com/dorukarslan/Pass-Guard/assets/79598598/c298826b-7611-48e6-8b3b-4fc7c9eaa38d)

## Advantages

Pass Guard offers a comprehensive approach to transaction security, combining face verification, secure access to card information, and blockchain transactions. It introduces an improved user experience, facilitating secure transactions with a few taps on the user's device. Furthermore, the system's capabilities to handle transactions and operations within the institution make it a versatile solution for a variety of use cases.
<img width="1190" alt="face" src="https://github.com/dorukarslan/Pass-Guard/assets/79598598/4f58b362-3367-4605-9bdf-55cf4d426cf6">

## Conclusion

Pass Guard is an innovative step towards a more secure, convenient, and sustainable transaction experience, significantly reducing the need for physical cards. Its implementation of face verification, blockchain transactions, and real-time monitoring forms a robust system that serves as a standard for future secure transaction systems.

Note

While this repository doesn't contain source codes, we welcome any feedback or suggestions on the project reports and the system explanation provided. Please feel free to contribute to this innovative journey towards secure and effortless transactions.


## App Screenshots
<p float="left">
  <img src="https://github.com/dorukarslan/Pass-Guard/assets/79598598/d685b40b-0e71-444c-99ed-d48805b3c1ea" width="33%">
  <img src="https://github.com/dorukarslan/Pass-Guard/assets/79598598/637fa0d5-1a64-4921-90d7-258d7f74ede7" width="33%">
  <img src="https://github.com/dorukarslan/Pass-Guard/assets/79598598/a385aa88-3b96-4909-a4ee-2768395c0e06" width="33%">
   <img src="https://github.com/dorukarslan/Pass-Guard/assets/79598598/c9ab0a64-2c22-4bbf-b52a-ac929aec72f1" width="33%">
</p>

