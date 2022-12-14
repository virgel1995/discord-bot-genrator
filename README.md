# Bot Generator 

<p align="center">
  <img src="https://img.shields.io/npm/dw/bot-genrator?style=social">
  <img src="https://img.shields.io/npm/v/bot-genrator?style=social">
  <img src="https://img.shields.io/github/forks/virgel1995/bot-genrator?style=social">
</p>

<p align="center">genrate diacord bot in few seconds this project is an clone of slappy!</p>

## What is Bot genrator?

Bot genrator is a CLI (Command Line Interface) tool that lets you generate a Discord.JS project in a matter of seconds.

## Why Bot genrator?

Do you use a Command/Event Handler? Are you tired of having to copy & paste the same files over and over again, or cloning a repository? Bot genrator serves as a purpose to eliminate the annoyance of doing that. Instead, with a simple command, Bot genrator will generate a base structure for your next Discord Bot Project.

It does so by using the most basic command & event handler. Simplicity is key. And since it works well, why change it? Regardless, if you need to try some things out without needing to re-write the same functions all the time, Bot genrator is great for that.

It also eliminates the abstraction away from users so they need not worry about how commands and events are registered. It will just work out of the box.

## What Bot genrator is NOT

- Framework
- Library
- Discord Bot (It is a Discord Bot Project **generator**)
- Replacement for coding

# Getting Started

Install  by running `npm install -g bot-genrator` or `yarn global add bot-genrator` on your terminal or Windows CMD. This will install bot-genrator globally.

- To create a project, type `genrator`, or simply type `genrator new <name of project>` in your Terminal or Command Prompt.
- Follow the steps and enter your Bot Token and Prefix.
- Once done, `cd` into your project by typing `cd <name of project>`
- To run the bot, type `npm run dev` or `yarn dev`. This will run the bot using `nodemon` which is installed locally.

## Generating Commands

- bot-genrator allows you to generate commands into categories. You can type `genrator` and select **Generate** to generate a command, or `genrator gen command`.
- It will ask you for a name, and then a category. This will generate all commands in the `src/commands` folder, in the correct category.
- You can also generate a command by typing `genrator gen command`. This will prompt you for a command name and category.

## Generating Events

- You can generate events by running `genrator gen event`, this will prompt you to select which events you would like to generate.
- To select event(s), press space bar and use the up and down arrow keys to navigate. Hit enter when you're done and your event files will be generated in the `src/events` folder.

## Will Bot-Genrator support TypeScript?

supports TypeScript

# Recipes
## COMMING Soon database selection with setup

### Integrating with Sequelize

```
Implementation Provided Soon
```

### Integrating with Mongoose

```
supports Mongoose 
```

### Integrating with MongoDB

```
Implementation Provided Soon
```

### Integrating with QuickDB

```
Implementation Provided Soon
```

