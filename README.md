# playground

The playwright playground

Begin here...

## Managing work in the TODO kanban

Install the TODO.md Kanban Board, and create TODO.md file in the root of your project

Set up the columns and the checkboxes like this:

```markdown
# This is your title

### TODO
- [ ] This todo task is a dash, space left bracket space right bracket
- [ ] You can manually

### In Progress
- [ ] Add more tasks
- [ ] To view the board, 

### Done

- [ ] To view the kanban use COMMAND + SHIFT + P and select Coddx: Todo Kanban Task Board
- [ ] Then you can add tasks and drag and drop columns from within that view

### Archive

```

## Commit messages: 

Use present tense, avoid the -m switch and add a more thoughtful commit in vim editor

## Install or upgrade nodejs

```bash
$ brew install node
```

```bash
$ brew upgrade node
```

## Initialize the project

```bash
$ npm init
```

Accept the defaults

## What demo sites are good for test automation practice:

Well Automation Panda has a great list
https://automationpanda.com/2021/12/29/want-to-practice-test-automation-try-these-demo-sites/

## Installing playwright

Init playwright and select TypeScript. 
Accept the defaults including yes to a default github workflow

```shell
$ npm init playwright@latest
```

## Installing playwright-watch

Work with playwright in watch mode, which means it will run the tests when they change

```shell
npm install playwright-watch --save-dev
```

Then you can run tests with

```shell
$ npm run test:watch
```

or 

```shell
npx playwright-watch test
```

## Instaling eslint for playwright 

Run the following

```shell
$ npm install -D eslint-plugin-playwright
```

