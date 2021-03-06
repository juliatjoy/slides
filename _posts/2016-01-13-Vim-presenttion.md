---
layout: slide
title: Vim text editor
description: A presentation slide for how to use Vim
theme: black
transition: slide
permalink: /vim-editor-tips
author: Ajay Joseph
post_thumbnail: /slides/images/vim-editor.jpg
profile_image: /slides/profiles/ajay-joseph.jpg
---

<section data-markdown>
# Vim

Jan 14, 2016
</section>

<!-- Just to show that markdown and html can be mixed -->
<section>
  <h4>Hi, I am</h4>
  <h3>Ajay Joseph</h3>
  <div style="width:150%;">
    <div style="float:left; width:30%;">
      <img alt="Jeroen De Meerleer" src="https://scontent-hkg3-1.xx.fbcdn.net/hphotos-frc3/v/t1.0-9/945390_3255807009318_1975357127_n.jpg?oh=1cbfba3bef55ba6fa91cb048a4808622&oe=5747C14D" style="float: left; width:300px; height:300px;">
    </div>
    <div style="float:right; width:70%;">
      <ul style="float: left; padding-top: 4%;">
          <li>Ruby Devoloper Trainee at Redpanthers</li>

      </ul>
    </div>
  </div>

</section>

<section data-markdown>
### Introduction

Vim editor is a clone of Bill Joy’s vi editor for Linux. Vim stands for Vi IMproved. Vim is designed for use both from a command line interface and as a standalone application in a graphical user interface. Vim is basically a open source application that is released under a license which includes some charityware clauses.

</section>

<section data-markdown>
### Introduction -- contd.

Even though vim is available both in command line as well as an application with GUI, vim is widely used in command line and the full functionality is expressed through its command line mode.

</section>

<section data-markdown>
### Vim -- modes

There are 2 modes in vim say INSERT mode and NORMAL mode.Mode in which you are currently in is displayed in editor.
Pressing i will take you to insert mode and press escape key to return to normal mode.

</section>

<section data-markdown>
### navigation

In contrast to the normal text editors, vim uses keys h,j,k,l to move the cursor. To navigate the text in terms of words, keys w,b and e are used.

</section>

<section data-markdown>
### navigation -- contd.

B moves cursor to the beginning  of the word,E to the end and W to the start of next word.

</section>

<section data-markdown>
### Number powered commands in vim

Commands in Vim can be combined with numbers to good effect

eg.5w is same as pressing w five times.

</section>

<section data-markdown>
### Inserting new content

Inserting into a new line is done by presing key'O'.Capital 'O'creates a line above the current line and 'o' creates it below the current line.

</section>

<section data-markdown>
### Searching in vim

 F or f is the key used for this. For e.g. Fo finds the next occurrence of o from the current cursor position.
 Search in Vim can be combined with numbers as in the previous cases. 3fo will find the third occurrence of o from the current position.

</section>

<section data-markdown>
### Searching in vim -- contd.

In Vim you press ‘/‘ and give the text you are looking for.Repeat the search to find the next occurrence of the same text by pressing n and previous occurrence by pressing N.

</section>

<section data-markdown>
### Matching Parenthesis/brackets

‘%’ key is used to find the matching parenthesis. %key  matches {,[,( to its corresponding closing.

</section>

<section data-markdown>
### Movement between lines

To reach the beginning of a line press 0 and $ key takes you to the end of the line.
G takes you to the end of the file and gg to the beginning of the file.

</section>

<section data-markdown>
### Movement between lines -- contd.

To navigate to a particular line, line number can be given along with G. e.g. 8G takes the cursor to the eighth line.
</section>

<section data-markdown>
### Occurrences of a word

To find the next occurrence of a word in which the cursor is currently in press ‘*’ and the previous occurrence can be found by using #.

</section>

<section data-markdown>
### Deleting

In line deleting is taken careof by 'x' and 'X'.‘x’ deletes the character the cursor is currently pointing to and ‘X’ deletes the character left of the cursor.
</section>

<section data-markdown>
### Deleting -- contd.

‘d’ is the delete command. It can be combined with movement. For e.g. dw deletes the first word on the right side of the cursor, it also copies the content by default so that it can be pasted somewhere else using ‘p’.

</section>

<section data-markdown>
### Repeating commands

The previously executed command can be repeated just by pressing ‘.’ for any number of times we want

</section>

<section data-markdown>
### Vim plugins

Vim plugins allow you to enhance, change, or add to Vim's existing behaviors. They're a powerful tool, and a key part of what has helped Vim remain relevant for 23 years, even as the computing world has changed dramatically around it. They allow Vim to support languages that didn't exist the last time its core was updated and also allow for powerful new features that benefit all users.

</section>

<section data-markdown>
### Plugin Management

Plugin management in vim has no official solution, as we have with other editors like sublime.  Pathogen was first plugin manager for vim but later on Vundle became more popular and took over its position.

</section>


<section data-markdown>
### Vimrc

Stands for vim runtime configuration  
The vimrc file contains optional runtime configuration settings to initialize Vim when it starts.

</section>
<section data-markdown>
### Plugin Management -- contd.

To configure vundle  
1.git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim  
2.add this code to top of .vimrc file  
  set nocompatible  
  filetype off  
  set rtp+=~/.vim/bundle/Vundle.vim  
  call vundle#begin()  
  Plugin 'VundleVim/Vundle.vim'  
  call vundle#end()  
3.lauch vim and run plugin install

</section>

<section data-markdown>
### Essential plugins for vim

vundle  
NERDTree  
Syntastic  
EasyMotion  

</section>

<section data-markdown>
### References

http://www.openvim.com  
http://vimawesome.com  
https://github.com/VundleVim/Vundle.vim  
https://github.com/scrooloose/nerdtree  
</section>

<section data-markdown>
##Thank you :)

</section>
