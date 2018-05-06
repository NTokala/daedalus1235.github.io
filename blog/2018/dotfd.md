---
title: Dawn of the First Day
subtitle: --72 hours remain--
date: 6 May 2018
use_math: true
---

# Topic the First: Blogs

I have been inspired by my learnèd colleague's [first (and only) blog post](https://logtothenthpower.wordpress.com/) to begin one of my own. To be honest this post will most likely be the only one that is added before I forget that I have made this entire website, unless @NTokala and I actually begin a podcast and we need somewhere to host it. Personally, I have mixed feelings about blogs. Many blogs, such as [Ndlessly](https://ndlessly.wordpress.com/), are incredibly useful, saving me from the boredom of many a high school math class in the past. Other tutorialized blogs, like [this](https://www.bloggingbasics101.com/how-do-i-start-a-blog/) and the one you're reading right now annoy me with their overly conversational tone. Then again, I and many others enjoy listening to podcasts like HI that are just casual conversations on seeminly random topics. 


This blog, at the moment, is somewhat of a personal experiment that shall answer two questions:

1. How long will it take for me to forget this exists, and how comfortable will I get with this task in the meanwhile?
2. How will my style of writing and style of formatting evolve, and how will the topics of focus shift?

If I can somehow keep doing this to the end of the month, I feel that there is a good chance that I might actually stick with this for a while, even if no one bothers to read it. It is somewhat fun and cathartic to just write down random thoughts. At the same time, I know for a fact that in a few years (or even a few days) I will feel mortified that I had ever created this. Everyone needs to be made fun of for something, and I seem to relish the thought of handing out that ammunition to everyone in my path. Anyway, on to an actual topic.

---

# Topic the Second: Tech 'n' Stuff

This page, as noted in the footer, was made using GitHub pages. Because I never bothered to learn HTML, I'm trying to use a combination of HTML, Jekyll, Markdown, and MathJax so that I have the versatility to make things pretty in the future. I really hope MathJax works, because then I'll be able to write pretty equations using $\LaTeX{}$, such as a proof for the Boltzmann Entropy Equation below. I am using my text-editor/IDE of choice, Notepad++, because it has a nice folder-as-a-workspace option and dark mode. Also I couldn't really be bothered to learn how to use Vim, but that might change now that I apparently have a free [Lynda](https://lynda.com) subscription. A lot of the HTML code I stole from a different website that I had been working on with some friends a few months ago, and I don't really remember how .yml stuff works so this will be fun. GitHub is great because it makes it easy to work with multiple tabs/files open in Notepad++ and still have the "code" and text easily uploaded.

### Boltzmann Entropy
Given $PV=NK_{B}T$, and assuming work$=-PdV$ and $dU=0$
$$
	\begin{align}
		w & =-\int PdV \\
		& =-Nk_{B}T\int \frac{dV}{V} \\
		& =-Nk_{B}T\ln{V}  
	\end{align}
$$
Then, using $dU=0$, we can rewrite the above expression in terms of q, resulting in
$$
	\begin{align}
		q &=Nk_{B}T\ln{V}
	\end{align}	
$$
Dividing by $T$, we can obtain an expression in terms of $\frac{q}{T}$, or $S$. Therefore,
$$
	\begin{align}
		S &= \frac{q}{T} = Nk_{B}\ln{V} \\
		&= k_{B}\ln{V^{N}}
	\end{align}
$$
However, raising volume to the number of particles in the system is effectively the same as the number of microstates. The volume represents the positions that an individual particle may be in, and the exponent the total number of permutations, or microstates, ($\omega$). As such, we reach the final equation, the Boltzmann Entropy Equation,
$$
	\begin{align}
		S &=k_{B}\ln{\omega}
	\end{align}
$$

# #