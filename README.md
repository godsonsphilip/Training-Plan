# Training-Plan

<details>
  <summary>Frontend</summary>

  | Task | Sources | ETA |
| ---| ---| --- |
| ReactJS | Watch till lecture 15 ➝ [Playlist](https://youtube.com/playlist?list=PLRAV69dS1uWQos1M1xP6LWN6C-lZvpkmq&si=BCgTkLXgu1CW9SKC)<br> | 7 days |
| NextJS | What is NextJS ➝ [Video](https://youtu.be/PiN5Op_Lnmw?si=8OBowcro3ShmehgD)<br>Server Components VS Client Components ➝ [Video](https://youtu.be/bugO1tmSDpM?si=z-AXpq9FWV0N7xYV)<br>Installation and examples ➝ [Doc](https://nextjs.org/docs/getting-started/installation)<br>Folder structure, don't read the `pages` Routing Conventions ➝ [Doc](https://nextjs.org/docs/getting-started/project-structure)<br>Routing fundamentals ➝ [Doc](https://nextjs.org/docs/app/building-your-application/routing)<br> | 5-6 Days |


</details>

<details>
  <summary>Backend</summary>

| Task | Sources | ETA |
| ---| ---| --- |
| NodeJS | What is NodeJS ➝ [Video](https://youtu.be/ohIAiuHMKMI?si=twjQmObGRLw0wBPK)<br>Installation<br>Windows ➝ [Doc](https://nodejs.org/en/download/prebuilt-installer)<br>Linux/Mac ➝ [Doc](https://nodejs.org/en/download/package-manager)<br>Hello World ➝ [Video](https://youtu.be/XhCs5cTYW_8?si=s4HcJ7xdyLwjfhV5)<br>Modules ➝ [Video](https://youtu.be/FSRo41TaHFU?si=k9dzKKF-DDr3iIGT)<br>How nodejs works(optional) ➝ [Video](https://youtu.be/y0aTs56DJWk?si=4-LLKwGFfqmvB0fz)<br> | 1-2 Days |
| Web Server | Building a web server using nodejs ➝ [Video](https://youtu.be/apuAWXMT-9c?si=eOoMgSjQBUL-ur5j) watch till 16:00<br>Building an express server ➝ [Video](https://youtu.be/J50hZTKXEyE?si=Eq_P-ZWWSiyZCeJp)<br>Database designing(optional) ➝ [Video](https://youtu.be/M85uM6gV-vI?si=ly4-NT61Vwtf3XMl)<br>Backend project structure(important) ➝ [Video](https://youtu.be/eDHl26DWrk4?si=aYGiPj6iXflMPkUu)<br> | 2 Days |
| MongoDB | Installation ➝ [Doc](https://www.mongodb.com/docs/manual/administration/install-community/)<br> | NA |
| ExpressJS Course | Follow this [playlist](https://youtube.com/playlist?list=PLu71SKxNbfoBGh_8p_NS-ZAh6v7HhYqHW&si=0Vl4-qVHrek60i-N)<br>NOTE:<br>Start from 5th video.<br>6th is optional(depends on you).<br>11th video is optional.<br>Watch till 18th video.<br> | 7 Days |

</details>

<details>
  <summary>WSL installation in Windows 11</summary>
  
  What is WSL -> [Link](https://learn.microsoft.com/en-us/windows/wsl/about)
  ### Installation steps
  1. Open CMD or Powershell with administrator and run the following commands:
     ```bash
     wsl --install
     ```

  2. Preferred distribution is Ubuntu, so to install Ubuntu in WSL, run:
     ```bash
     wsl --install -d Ubuntu
     ```
     
  3. If you prefer some other distribution, you can run the following command and select your desired distribution:
     ```bash
     wsl --list --online
     ```

  4. Restart your PC after the above steps. Ubuntu or your selected Linux distribution will be installed.
  5. You can run it by running this in your terminal:
     ```bash
     wsl -d Ubuntu
     ```
     OR
     ```bash
     wsl -d <Distribution Name>
     ```
     To list all the distributions installed, you can run:
     ```bash
     wsl -l -v
     ```
  6. Then it will ask for a basic setup like your username and password.
  7. Before installing anything, update and upgrade your Linux by running,
     ```bash
     sudo apt update
     ```
     Then run,
     ```bash
     sudo apt upgrade
     ```
     NOTE: It will ask for your password, just type it and press enter.

  8. In future, when you need to increase the RAM and swap space of your WSL, you have to create a file in the location, `C:\Users\<UserName>\.wslconfig`. Make sure this file name should be only `.wslconfig`, but not `.wslconfig.txt`. Contents of the file would be:
     ```
     [wsl2]
     memory=4GB
     swap=8GB
     ```
     NOTE: You can't increase your memory more than the available memory in your system.
  
</details>


### Typescript [playlist](https://youtube.com/playlist?list=PLRAV69dS1uWRPSfKzwZsIm-Axxq-LxqhW&si=YEZ5jDc1pdjp7OUS), watch till lecture 15.

### Github course [playlist](https://youtube.com/playlist?list=PLRAV69dS1uWT4v4iK1h6qejyhGObFH9_o&si=A0W0AaGE0rTOWCYD)
