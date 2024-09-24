# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch`
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.

## Port Killing
kill -9 $(ps aux | grep cds-dk | awk '{print $2}')

## Debug
bash
sed 's#$"SSH_CONNECTION"#"$SSH_CONNECTION"#gi' -i $HOME/.bashrc



##Jest Test
npm add -D axios chai@4 chai-as-promised@7.1.2 chai-subset jest

