# Getting Started

## Add basic svelte project to your repository.

1. Add ProjectName variable specific to your project.
```
#!/bin/bash
ProjectName=my-app
echo "Project Name : $ProjectName"
echo "Cloning svelte-frontend-base git repo"
git clone https://github.com/sunnyRavindra/svelte-frontend-base.git $ProjectName
echo "Moving to project"
cd $ProjectName
echo "Preparing npm project"
npm install
echo "Base Project install done"
```
2. Add routes.
```
#!/bin/bash
Routes=(
"/about"
"/contact"
"/autoarch"
)
echo -e "$Routes\n"
```