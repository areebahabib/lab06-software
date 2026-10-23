# Challenge Answers

1. Job 1: Install htop and write one thing it shows
Command: sudo apt install -y htop
Answer: It shows system memory (RAM) usage, CPU core usage, and running process list.

2. Job 2: Version of apache2 offered
Command: apt show apache2
Answer: Apache version offered is 2.4.58 (or version shown in apt show).

3. Job 3: Number of installed packages
Command: apt list --installed | wc -l
Answer: Around 780+ packages are installed.

4. Job 4: Run alpine Docker container
Command: sudo docker run --rm alpine echo "Hello from Alpine"
Answer: Prints "Hello from Alpine".

5. Job 5: Full path of Docker key file and sources file
Command: ls /etc/apt/keyrings/docker.asc && ls /etc/apt/sources.list.d/docker.sources
Answer: 
Key file path: /etc/apt/keyrings/docker.asc
Sources file path: /etc/apt/sources.list.d/docker.sources

6. Job 6: Remove htop and prove it is gone
Command: sudo apt remove -y htop && hash -r && htop
Answer: Shows "Command 'htop' not found".
