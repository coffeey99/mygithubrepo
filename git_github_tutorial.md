Update the installed Git from https://git-scm.com/

Open Git Bash

<img width="792" height="498" alt="image" src="https://github.com/user-attachments/assets/c1ad4e21-d7b0-49a0-8f8c-a3de57fcf858" />

Verifying the installation

<img width="795" height="815" alt="image" src="https://github.com/user-attachments/assets/548efc95-0c18-404d-a507-ca4779cfe264" />

Set Email-Address for commits:

<img width="563" height="1018" alt="image" src="https://github.com/user-attachments/assets/4d8efb19-779b-4771-93e2-2d51dfc41cd4" />

Set name for commits:

<img width="426" height="1133" alt="image" src="https://github.com/user-attachments/assets/826ddc70-dd12-420f-b973-fb39ed2e00f0" />

Get config list:

<img width="570" height="1540" alt="image" src="https://github.com/user-attachments/assets/c79544b2-d794-4080-9ad1-bcdb66600755" />

Make a repo and initialise git:

<img width="687" height="1810" alt="image" src="https://github.com/user-attachments/assets/e052a965-af92-465b-9d7f-f252b9d2184a" />

Create an index.html file, either with text editor or VS Code and save it in the same directory.

Show file with "ls"

<img width="606" height="1969" alt="image" src="https://github.com/user-attachments/assets/1b8b5160-5b34-457a-a97f-a772599718ac" />

<img width="760" height="2061" alt="image" src="https://github.com/user-attachments/assets/321371c0-7d01-4234-ae5f-bc3dbc025f52" />

If the file is red, it means it is untracked. A tracked file is a file that Git is watching for changes. We have to add it to "staging environment" and after that commit it. Then it will be tracked.

<img width="599" height="2407" alt="image" src="https://github.com/user-attachments/assets/7145b3e4-abe6-440d-a221-a97c8adc3e8a" />

and then commit

<img width="644" height="2664" alt="image" src="https://github.com/user-attachments/assets/b411112f-f810-4bb2-9c47-daf2bb0299e3" />

View commit history

<img width="707" height="2833" alt="image" src="https://github.com/user-attachments/assets/1d98484b-73c0-497f-a412-96c4e2b99ffe" />

Connect Git with GitHub

1. Sign Up for GitHub
2. Create a repository

<img width="746" height="256" alt="image" src="https://github.com/user-attachments/assets/32205ce8-08f3-4404-9c3d-102af6bc0432" />

<img width="979" height="844" alt="image" src="https://github.com/user-attachments/assets/2916c7ab-ad77-4534-89c6-4975a57edcff" />

Since we have a local repository and want to push it to GitHub, we will using this option (later):

<img width="1543" height="219" alt="image" src="https://github.com/user-attachments/assets/96f29648-5f7b-40bc-90f7-1efa1745180f" />

To connect to GitHub, we need SSH. If you havent used SSH before, you need to create a private and a public key. Keep private key alsways private. Public key can be shared.

<img width="862" height="4829" alt="image" src="https://github.com/user-attachments/assets/759ae3b5-24e3-4123-b7b8-f7357046ac2d" />

After creating public and private key, add it to the SSH agent so Git can use it:

<img width="646" height="5181" alt="image" src="https://github.com/user-attachments/assets/d7a03f0c-bb21-42ac-998b-bde408dbf976" />

Copy public key to clipboard:

<img width="526" height="5312" alt="image" src="https://github.com/user-attachments/assets/eb85e36c-1253-4d4c-b05f-c771a9297fa0" />

$ clip < ~/.ssh/id_rsa.pub

And then add to GitHub

<img width="341" height="814" alt="image" src="https://github.com/user-attachments/assets/581b07e9-e894-477c-841f-9967d7db2f20" />

<img width="412" height="654" alt="image" src="https://github.com/user-attachments/assets/9075ffd0-9223-475d-adf6-78e24b42378c" />

<img width="1230" height="87" alt="image" src="https://github.com/user-attachments/assets/aad2162b-7007-438c-8579-0b2692a80f29" />

<img width="1204" height="618" alt="image" src="https://github.com/user-attachments/assets/8918ab04-bb22-44c9-bfc8-1ad32bc1e72d" />

Now we can connect via SSH with GitHub

<img width="1548" height="211" alt="image" src="https://github.com/user-attachments/assets/a6d9f62f-7e93-4a41-912e-4923cd91e11a" />

<img width="857" height="8180" alt="image" src="https://github.com/user-attachments/assets/7c33dca1-2b59-46a5-b7ca-68195f5a91c3" />

So we are not connected with GitHub.
