# Integer Jeopardy

## Overview

This web application seeks to provide an educational game for use in learning or reviewing material.  Users may create _games_ that consist of categories of items.  A participant in a game will select one of these items and all participants will then have an opportunity to answer the question for that item (or provide the question for that answer if following traditional Jeopardy rules).  Participants who provide the correct response are then awarded points.  The winner of the game is the participants with the most points after all items have been selected.

## Caveats

Identifying correct responses cannot be easily automated without significant investments in artificial intelligence.  This project currently has one developer and a budget of $0, making any such investments impractical.  The creator of the individual game must therefore serve as both the host and judge, managing the game and determining whether responses from the participants are sufficiently close to the expected response.

## Etymology

This web application is based on the [Jeopardy!](https://www.jeopardy.com/) game show.  However, Jeopardy! includes a _Double Jeopardy_ round, and double jeopardy is prohibited under our Fifth Amendment rights.  Since the Information and Computer Sciences (ICS) undergraduate program at the University of Hawaii at Manoa is based in Java, the natural result of excluding `double`s would be integers.