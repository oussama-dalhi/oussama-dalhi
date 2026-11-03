# Hi, I'm Oussama

I like understanding what happens underneath frameworks and abstractions. I write C for systems programming and build web apps with Python, FastAPI, JavaScript and React.

I'm currently focused on C, Linux and networking, alongside backend and frontend web development, and I like building tools that solve real problems.

## What I'm Working On

- **Systems & Networking:** C, Linux, sockets, TCP/IP and HTTP, plus memory management and file I/O.
- **Backend:** REST API design, SQL databases and Prisma ORM, authentication, caching and rate limiting.
- **Frontend:** JavaScript, React and Tailwind CSS.
- **CS Fundamentals:** Data structures, algorithms and problem solving.

## Featured Projects

### [YouTube Transcript Extractor](https://github.com/oussama-dalhi/youtube-transcript-extractor)

A full-stack application for extracting YouTube transcripts and managing saved transcript history. **[Live demo](https://transcript.oussama-dalhi.dev/)**

- Optional user authentication and persistent transcript history.
- PostgreSQL database with user-specific transcript storage.
- In-memory caching and API rate limiting.
- Deployed on FastAPI Cloud with Neon PostgreSQL.

`Python` · `FastAPI` · `JavaScript` · `PostgreSQL`

### [HTTP Server in C](https://github.com/oussama-dalhi/c-http-server)

An HTTP server written in C that serves static files from any directory, with custom 404 handling and path traversal protection.

- Built on raw TCP sockets, with its own HTTP request parser.
- Written first with Winsock on Windows, then ported to Linux with POSIX sockets.

`C` · `Winsock` · `POSIX Sockets` · `HTTP`

### [cViewer](https://github.com/oussama-dalhi/cViewer)

A lightweight image viewer written in C using SDL2 and stb_image.

- Loads images from the command line and renders them in an SDL2 window.
- Automatically resizes while preserving image aspect ratio.
- Built with Make. [Releases](https://github.com/oussama-dalhi/cViewer/releases) available.

`C` · `SDL2` · `Make` · `Linux`

### More Projects

- [**OBD-II Error Code Lookup**](https://github.com/oussama-dalhi/obd-code-lookup) ([live demo](https://obd.oussama-dalhi.dev/)): Look up vehicle diagnostic trouble codes, including symptoms and possible fixes (`JavaScript` · `HTML` · `CSS`).
- [**German Learning App**](https://github.com/oussama-dalhi/de-learn-german): Learn German vocabulary and common phrases based on your level (`React`).

## Open Source

**[pdfcraft](https://github.com/storytold/pdfcraft)**: Contributed UI fixes to an open-source PDF toolkit.

- [#696](https://github.com/storytold/pdfcraft/pull/696): Made the command palette close when clicking outside it, in addition to the existing Esc shortcut.
- [#1121](https://github.com/storytold/pdfcraft/pull/1121): Fixed the text-selection cursor appearing on the "All tools" toggle.

## Tech Stack

- **Languages:** C · Python · JavaScript · TypeScript · SQL
- **Systems & Networking:** Linux · POSIX Sockets · TCP/IP · HTTP
- **Backend:** Node.js · Express · FastAPI · Prisma · PostgreSQL · REST APIs
- **Frontend:** React · Tailwind CSS · HTML · CSS
- **Tools:** Git · GitHub · Vim · GCC · Make · Neon

## Get in Touch

- LinkedIn: [oussama-dalhi-dev](https://www.linkedin.com/in/oussama-dalhi-dev/)
- Email: [oussamadalhi5@gmail.com](mailto:oussamadalhi5@gmail.com)

---

```c
#include <stdio.h>
#include <stdlib.h>

int main(void)
{
    printf("Build. Learn. Repeat.\n");
    return EXIT_SUCCESS;
}
```
