<div align="center">
  <a href="https://www.youtube.com/channel/UCMwVTLZIRRUyyVrkjDpn4pA">
    <img alt="AI Agents Masterclass" src="https://i.imgur.com/8Gr2pBA.png">
    <h1 align="center">AI Agents Masterclass</h1>
  </a>
</div>

<p align="center">
  Artificial Intelligence is the #1 thing for all developers to spend their time on now.
  The problem is, most developers aren't focusing on AI agents, which is the real way to unleash the full power of AI.
  This is why I'm creating this AI Agents Masterclass - so I can show YOU how to use AI agents to transform
  businesses and create incredibly powerful software like I've already done many times! 
  Click the image or link above to go to the masterclass on YouTube.
</p>

<p align="center" style="margin-top: 25px">
  <a href="#what-are-ai-agents"><strong>What are AI Agents?</strong></a> ·
  <a href="#how-this-repo-works"><strong>How this Repo Works</strong></a> ·
  <a href="#instructions-to-follow-along"><strong>Instructions to Follow Along</strong></a>
</p>
<br/>

## What are AI Agents?

AI agents are simply Large Language Models that have been given the ability to interact with the outside world. They
can do things like draft emails, book appointments in your CRM, create tasks in your task management software, and
really anything you can dream of! I hope that everything I show here can really help you dream big
and create incredible things with AI!

AI agents can be very powerful without having to create a lot of code. That doesn't mean there isn't room though
to create more complex applications to tie together many different agents to accomplish truly incredible things!
That's where we'll be heading with this masterclass and I really look forward to it!

Below is a very basic diagram just to get an idea of what an AI agent looks like:

<div align="center" style="margin-top: 25px;margin-bottom:25px">
<img width="700" alt="Trainers Ally LangGraph graph" src="https://i.imgur.com/ChRoV8W.png">
</div>

<br/>

## How this Repo Works

Each week there will be a new video for my AI Agents Masterclass! Each video will have its own folder
in this repo, starting with [/1-first-agent/](/1-first-agent) for the first video in the masterclass
where I create our very first AI agent! 

Any folder that starts with a number is for a masterclass video. The other folders are for other content
on my YouTube channel. The other content goes very well with the masterclass series (think of it as
supplemental material) which is why it is here too!

The code in each folder will be exactly what I used/created in the accompanying masterclass video.

<br/>

## Instructions to Follow Along

The below instructions assume you already have Git, Python, and Pip installed. If you do not, you can install
[Python + Pip from here](https://www.python.org/downloads/) and [Git from here](https://git-scm.com/).

To follow along with any of my videos, first clone this GitHub repository, open up a terminal,
and change your directory to the folder for the current video you are watching (example: 1st video is [/1-first-agent/](/1-first-agent)).

The below instructions work on any OS - Windows, Linux, or Mac!

You will need to use the environment variables defined in the .env.example file in the folder (example for the first video: [`1-first-agent/.env.example`](/1-first-agent/.env.example)) to set up your API keys and other configuration. Turn the .env.example file into a `.env` file, and supply the necessary environment variables.

After setting up the .env file, run the below commands to create a Python virtual environment and install the necessary Python packages to run the code from the masterclass. Creating a virtual environment is optional but recommended! Creating a virtual environment for the entire masterclass is a one time thing. Make sure to run the pip install for each video though!

```bash
python -m venv ai-agents-masterclass

# On Windows:
.\ai-agents-masterclass\Scripts\activate

# On MacOS/Linux: 
source ai-agents-masterclass/bin/activate

cd 1-first-agent (or whichever folder)
pip install -r requirements.txt
```

Then, you can execute the code in the folder with:

```bash
python [script name].py
```
