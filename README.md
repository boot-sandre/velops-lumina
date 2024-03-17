# VelOps Lumina. Manage you photo album

- **Api server** using [Django Ninja](https://github.com/vitalik/django-ninja)
- **Vitejs frontend** using [Vuejs](https://vuejs.org/)
- **Spaninja project template** Using [Spaninja](https://github.com/synw/django-spaninja)

## Features

- Explore and sort photo collection
- Use Genai to generate and mix picture 
- Use ai Agent to help user in repetitive task

<div align="center">
<img src="docsite/public/haunted_house.png" alt="" />
</div>

## Development 

### Code quality

This project uses [Pycheck](https://github.com/emencia/pycheck) to monitor the quality of the code. To install
the code quality tools:

```bash
make install-pycheck
# or
yarn global add @pycheck/cli
yarn global add @pycheck/ui
# or
npm install -g @pycheck/cli
npm install -g @pycheck/ui
```

#### Analysis and history

Run:

```bash
pycheckui
```

Open `localhost:5143` in a browser to run an analysis. Note: this uses a `.pycheck.db` local Sqlite file
to store the code quality history

#### Command line

To do a quick check in the command line (not recorded in history):

```bash
pycheck
```

