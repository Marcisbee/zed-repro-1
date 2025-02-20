# zed-repro-1

## Step 1
```sh
cd ./project-a && npm i && zed .
```

## Step 2
Open `main.js` file in zed editor and run "editor: format" command.

## Step 3
Verify:
- biome.json says to have double quotes and nothing changed, because it already has double quotes in main.js.

## Step 4
Now, do not close previous zed window with project-a!

```sh
cd ./project-b && npm i && zed .
```

## Step 5
Open `main.js` file in zed editor and run "editor: format" command.

## Step 6
Verify:
- biome.json says to have SINGLE quotes and nothing changed, even tho main.js has single quotes.
