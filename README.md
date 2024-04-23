# Course of Interest
## x86 Assembly with NASM

![image](https://github.com/Apollo-Apostolos/Learning-x86-with-NASM/assets/53583068/ad7c1a11-8b49-4f74-8754-406d58501e4b)

![image](https://github.com/Apollo-Apostolos/Learning-x86-with-NASM/assets/53583068/dcb669ac-5014-4ea3-b85b-1b767a95b197)


## Where Is This Course?
It's on YouTube.
Also available via Invidious[^1]: https://yewtu.be/channel/UC7KBXRtv-EkiOFsRtpBxIbg/playlist?list=PL2EF13wm-hWCoj6tUBGUmrkJmH1972dBB


## Is The Course Relevant?
Pretty sure the course remains quite relevant. It's working on my end, 2024. 
### Does the Course's Software have Bugs?
Might have discovered a bug in GDB. It's typography "(gdb)" turned blue. How I did that has already been forgotten. But, I took a screenshot. I'll try to reproduce the bug. Then share it with  people developing GDB. (or maybe it's a feature)

## Preparation Requirements?
### Portable Aliases ~ .bashrc
It helped me to have .bashrc Portable Aliases quickly process the code-files, else you'd be doing these three steps:
1. Compile into Machine Code? 
2. Link in Libraries like a mad-lib game? 
3. Pipe through GDB (the debugger)

When it could be one:

```bash
run assembly_quick_compile_link_debug.sh 
```

### NeoVim
After I learn from ThePrimeagen-&-TJDev to get my NeoVim set up, then it's on to
- bringing in my x86_64 Linux Assembly notes
  {screenshots, commentary, questions}
- organizing a parallel chronology 
  {numbering videos, mapping trains-of-thought}

## What's my Status?
I needed weeks to learn a BASH script which merely added headers around outputs of hardware-information. Its uses AWK; I've already forgotten how I did any of it.

Then months went by. I started to wrap my head around SystemD when getting my MACChanger & Host-Name Randomizer script running. or so I thought. Wiki's are great if you know the context of what you're reading....... SystemD is simple. But you have to know the ecosystem you're parachuting into to make sense of the sounds of the wild echoing towards you.
 
 Since diving into the Linux Assembly language my understanding for how computers worked has shifted -- drastically. First, holy fucking shit! Our computers compute maths, video-presentations, and then there's the security-checks performed on top each-and-every `syscall` sent to our CPU?! What???

The overhead on security is enough to baffle me silly. I'm surprised these things aren't bugged out and crashing from proverbially exhausting our kernel-files. Seriously though, **Why does the CPU not check security at the door?**

The CPU brings in our `syscall` macro's/templates already filled out from the `eax` register.
It brings those into Level 1 Cache (or was it a Ring Level?) to then reach up asking the Kernel, 

>	"Hey, you think we can let this guy in? (whom it already brought into Level 1 !)
>		Here's his credentials."
>		 \<insert_UID_GUID_PID_stuff>
>		 \<show_the_DAC_MAC_LSM_stuff>

So apps arn't required to take off the muddy shoes outside the house?
O.o With so many processes running through Level 1, it's getting muddy.


Uhm,

Assembly could have been a breeze to learn. Watch videos, Take notes, Sleep well.
I didn't realize how nuanced the programming ecosystem has grown into, nor how intricate my hurdles would be. Crawling to walking was an easy transition. Walking to then realizing, that for a while now, both kneecaps had been blown out, well that's an immediate realization. I do not know what the next step is. Although it's been difficult as hell, I hope to share as much of it with you as possible.


[^1]: Invidious instances are servers paid-for and hosted-by strangers. However, these mitigate YouTube's Link-Jacking. Hyperlinks arn't redirected through YouTube's **House of** ~~Mirrors~~ **Malware**.   Gotta trust someone, somewhere. Choose an Invidious Instance here: [choose_invidious_instance](https://docs.invidious.io/instances/#list-of-public-invidious-instances-sorted-from-oldest-to-newest)
