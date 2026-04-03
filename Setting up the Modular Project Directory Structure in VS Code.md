# What we will learn in this repo is how to seperate the agent files Like: (an file is about the dashboard another about vector databases and another about tools, etc)

## Why should we do that?

## Because we will move tottaly freely instead of just rekying on one file that in it everything then it's will become soo complex and hard for reading, working, etc because let's say we want to add another tool if we seperate the file we can easily go to tools file and add the tool that we want, But if we have one file combine in it everyhting then we will take a lot of time to find where is the tools is and after we found it and we add now how can i make everything interact to eatch other??

***Soo it's will be so hard for doing all of this in just one signle file***

### ok how can i do it?

**Make these files in your vs code:**

```
/my-ai-agent
├── data/               # Persistent storage for vector databases
├── logs/               # Operational logs for debugging agent decisions
├── src/                # Core source code
│   ├── __init__.py     # Makes src a python package
│   ├── agent.py        # Main loop: perception, reasoning, action
│   ├── memory.py       # Vector DB integration (ChromaDB)
│   ├── tools.py        # External function definitions
│   └── utils.py        # Helper functions and environment loaders
├── .env                # Secret keys and local configurations
├── app.py              # Streamlit frontend entry point
└── requirements.txt    # Project dependencies
```

