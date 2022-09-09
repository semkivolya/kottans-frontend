# kottans-frontend

## Front-end stage 0 learning summaries

## [x] 0. Git Basics  

I liked that lectures are concise and included built-in tests.

The game that teaches Git was really interesting though I would love it to be less abstract 
and include some short pieces of code that are stored in example repositories we are working with
so that I could better understand the purpose behind some git commands I had to execute.

The Git is a bit overwhelming in comparison to the Mercurial which I used.

___

## [x] 1. Linux CLI, and HTTP

-  Linux CLI <details>
        <summary></summary>

    ![Quiz 1 results](task_linux_cli/1.png)
    ![Quiz 2 results](task_linux_cli/2.png)
    ![Quiz 3 results](task_linux_cli/3.png)
    ![Quiz 4 results](task_linux_cli/4.png)
    ![Final words](task_linux_cli/final_word.png)

    </details>

    
    **New:**  Since I am new to linux cli, basically all commands except for cd and mkdir were new to me.   
    **Surprised:** That a command used for moving and renaming files is the same.  
    **Plan to use:** Commands "more and find" seem to be the ones that I will use.  

- HTTP part 1  
    **New:**  The notion of multiplexing(client is able to send multiple requests simultaneously) that was introduced with version 2.0.  
    **Surprised:** Some headers are common for request and response messages. Via header where intermediate proxies or gateways inject their IP or DNS names.  
    **Plan to use:** Tools that allow to monitor HTTP communication, for example: Chrome inspector, Wireshark. 
- HTTP part 2  
**New:**  Persistent TCP connections that were introduced in HTTP 1.1 that stay open until client closes them and can be reused.  The notion of Fat URLs, Digest Authentication, pool of connections.  
**Surprised:**  Multiple caching proxies, Cache-control header values.  
**Plan to use:** Cookies, cache, basic authentication.

___

## [x] 2. Git Collaboration

- Learn branching <details>
    <summary></summary>

    ![Git basics](task_git_collaboration/branching1.png)
    ![Git remote repositories](task_git_collaboration/branching2.png)</details>  
**New:** Git tags, rebase.  
**Surprised:** Local main branch is not necessarily directly mapped to the remote main branch. The obsession with keeping commit history clean hence avoiding merge commits.     
**Plan to use:** Cherry-pick.
- Git and github <details>
    <summary></summary>

    ![](task_git_collaboration/gitgithub.png)</details>
**New:**  Squashing commits, rebasing.  
**Surprised:**  Squashing commits.  
**Plan to use:**  Well, eventually everything.