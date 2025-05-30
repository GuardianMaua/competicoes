# competiçoes

This repository is intended to store all the write-ups from competitions the entity has participated in. Here, you will find various solved CTFs from different events, with each CTF potentially having multiple versions..

## Structure 🧱

The directory structure is as follows:

```bash
├── <CTF event>
│   ├── README.md
│   ├── <CTF>
│   │   ├── README.md
│   │   ├── <CTF version>
│   │   │   ├── writeup.docx
```

Each platform will have a directory named after it, containing a README.md file with a brief description of the platform and the solved CTFs. Inside the CTF directory, there will be a README.md file with a brief description of the CTF and the write-ups for each version of the CTF. Each version directory will be named after the user responsible for the write-up.

## How to Contribute 🤔

To contribute, simply follow these steps:


1. Clone the repository;
2. Create a branch with the following pattern: `<event lowercase>_<ctf name lowercase>_<github user>`;
3. Write your resolved write-up;
4. Add the write-up to the corresponding folder;
    - If the folder for the event does not exist, contact one of the coordinators;
    - If the folder for the CTF does not exist, create it;
    - Create your own folder, naming it after your GitHub username.
5. Commit with the message: `feat(<ctf name>): add write up`;
6. Push to the created branch;
7. Open a pull request;
8. Wait for a coordinator to review it, and if everything is correct, your pull request will be accepted.


