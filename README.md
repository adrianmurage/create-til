# The Create TIL note project

This project aims to make it easy for me to create learning exhaust, an idea I picked up from Swyx blog post on [learning in public](https://www.swyx.io/learn-in-public/). The type of learning exhaust I setteled on was til(today I learned) notes on the fly.

To keep up with the habit, the process to write and publish them needs to be frictionless. Thus was born the Create TIL note project. 

It aims to make it possible to publish til's to my blog without needing to do anything other than write up the note in my favourite editor (vscode). 

It aims to automate:
1. The adding of front matter to the til note
2. The git add, commit, push process

Once the notes are pushed to GitHub, an automation that auto publishes recent pushes to the repo will pick it up from there and publish the tils on my blog.

The idea came from [leebyron](https://leebyron.com/til/). This [YouTube video](https://www.youtube.com/watch?v=iJn9kZw-hw8&t=4s&ab_channel=LeeByron) expounds on what I aim to do. 


## The Process
I am currently using [this tutorial](https://www.twilio.com/blog/how-to-build-a-cli-with-node-js) to create the cli tool for the create til project.