# emacs-datafied
The manuals for both Emacs and Org mode are both extremely dense and opaque. This is an effort to make the information in those manuals more parsable and searchable

## Preamble
I find a lot of utility out of [Org Mode](https://orgmode.org/) and thought it was a powerful tool more people should know about. However the Org Mode manual is dense, opaque, and daunting for users unfamiliar with Emacs. The end goal of this project would be to use the functionality of org mode as an inroads to understanding and using emacs. Creating documentation and tutorials in Org Mode that help users build their knowledge of both Org Mode and Emacs in a more gradual way.

## Current State
Currently, the project is simply trying to parse some of the crucial information from the Emacs manual and the Org Mode manual. One of the benefits of how the information is being parsed is if you are looking for a command or a variable that relates to the window, you can search for commands by tag. Paradoxically, one needs to know some Org Mode to make use of searching for tags, so presently this project is not the most helpful to those I would be trying to reach. The hope is that after parsing all of the information in this way, it will be easier to determine which is the minimum amount of information a user needs to get started in Emacs, and get started in Org Mode. Then after writing documentation for how to get started, the documents that are currently being written would be a very helpful resource.

## Helping
If you are interested in this project I can envision a few different ways to participate that would be helpful

### Emacs Set Up Instructions
The instructions for how to set up Emacs for both decent aesthetics and installing MELPA do not seem to all be in one place. I would love for someone to write up those instructions that assumes no familiarity with the command line.

### Inconsistencies
If you are familiar with Org Mode and would like to look through what I have worked on so far and notice any inconsistencies with how I am parsing the data into org mode, I would love for you to write up an issue.

### Most Used Commands/Variables and Workflows
I have not been able to find many places online that details the Commands/Variables and Workflows they use most often with Emacs and/or Org Mode. Sending those along would be very helpful. It would be even more helpful if you categorize the commands you use:

#### Necessary
These are commands or other features that if you didn't know about them, it would be near impossible to use Emacs or Org Mode. I'm talking about
- `keyboard-quit`
- `next-line`
- `find-file`
- or the concept of Windows in Emacs.

#### Common
These are commands or other features that if you didn't use these commands Emacs would be really annoying to use, but not impossible. I'm thinking about
- `move-beginning-of-line`
- `forward-word`
- `kill-line`
- or the concept of Modes (Major or Minor)

#### Shortcuts
These are commands or other features that helped you build confidence with Emacs and Org Mode. You probably learned them early on, and you use them regularly, but they are not used in every Emacs Workflow. It's safe to wait a little bit before learning about these commands or features. I'm thinking of commands like 
- `goto-line`
- `describe-key`
- or recording and using an unnamed macro.

#### Niche
These are commands or other features that you only ran into after running into a workflow specific issue. They are perfect for exactly what they are suited to, but not everyone runs into them. Commands like
- `fill-paragraph`
- `set-fill-column`
- `list-directory`
- or more in depth knowledge of Macros or other helpful Modes.

#### Esoteric
These are commands that you consistently have to look up. You don't encounter them very often, they aren't stapes in a workflow, maybe you don't even use them. Maybe you just know about them, or someone you know loves them, but you aren't really sure why. Or maybe you set them up once and never had to touch them again. The stuff that you appreciate there is good documentation for it. I'm thinking of commands like
- `tex-latex-block`
- `kbd-macro-query`
- or using RMail.
