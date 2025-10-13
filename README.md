# CPPT-Certification

<img width="1103" height="847" alt="image" src="https://github.com/user-attachments/assets/a0039e1a-d20d-436b-9e77-7f990daef8a1" />


**Review - Guía CPPTv3 INE**

Hola, muy buenas. Esta va a ser una pequeña guía con consejos sobre cómo hacer la CPPTv3 del INE.

**Mi opinión:**

Lo primero de todo, no creo que sea un examen complicado, pero necesitas una buena base y saber lo que estás haciendo. Considero más importante todo lo que vayáis aprendiendo por el camino que la certificación en sí, porque simplemente será un reflejo de los conocimientos que tengáis.

No vale la pena comprar el voucher de 600$ con acceso a la formación del INE. Tampoco creo que valga la pena gastarse 400$ por el voucher normal. En mi caso, todas las certificaciones que tengo del INE las he cogido con descuento del 50% (tanto la eJPT, CPPT y eWPT). Igual por unos 400$ he podido conseguir las tres. De otra forma, no vale la pena en mi opinión personal...

Esta gente suele sacar descuentos cada 3-4 meses. En mi caso, lo que hice fue dejarme la pestaña del INE fijada en el navegador y todos los días, durante bastantes semanas, ir entrando a revisar.

**Mi experiencia:**

Realmente llevo un poco más de un año en el mundo de la ciberseguridad y he ido estudiando a ratos lo que he podido mientras trabajaba. Seguramente lo que yo he conseguido se pueda hacer en mucho menos tiempo optimizando y teniendo una buena hoja de ruta. Siempre he ido estudiando por mi cuenta con HackTheBox y videos que encontraba por YouTube, pero considero que en gran parte el contenido de la plataforma de HackTheBox es el que me ha hecho estar donde estoy.

Consiguiendo el plan estudiante, que son como 10$ al mes, tienes acceso a muchísimo contenido de calidad y bien estructurado. A mí HackTheBox no me paga por mencionarlos, simplemente explico cómo ha sido mi camino hasta llegar aquí.

Pues eso, estudiando por mi cuenta, haciendo los paths de HackTheBox y pillándome el premium para hacer los laboratorios, fui aprendiendo. Por unos 25$ tienes el pack completo práctica/teoría. Me compré el voucher para hacer la eJPTv2 y la hice hace 4 meses.

Es decir, entre la CPPT y la eJPT han pasado 4 meses, por temas varios, pero seguramente puedas obtener el salto entre 1-2 meses.

**Recursos:**

**HackTheBox Academy:**  
[https://academy.hackthebox.com/module/details/143](https://academy.hackthebox.com/module/details/143)  
Vale la pena pagar el módulo y pegarle fuego.

**HackTheBox Labs:**  
[https://app.hackthebox.com/](https://app.hackthebox.com/)  
Vale la pena pagar el VIP un par de meses y pegarle fuego.

Estas son las máquinas que yo he hecho:

## HACKMYVM

DC01  
DC02  
DC03  
DC04

## HACK THE BOX

MANAGER  
ACTIVE  
MONTEVERDE  
RESOLUTE  
SAUNA  
FOREST  
HOSPITAL  
INTELLIGENCE  
CICADA  
HOSPITAL  
HEIST  
ADMINISTRATOR  
RETURN  
TIMELAPSE  
JEEVES  
CERTIFIED  
JAB  
STREAMIO

Las de HACKMYVM son completamente gratis.

Haciendo estas máquinas, teniendo una buena base y habiendo completado el módulo de HackTheBox, vais completamente sobrados.

**Cosas a tener en cuenta:**

- **Leer muy muy bien las preguntas y dejarlas estructuradas.** Las preguntas están desordenadas, no van por orden, por máquina ni nada por el estilo. Leerlas completamente y entenderlas te va a ahorrar mucho tiempo y esfuerzo. Son las que te van a guiar por el camino y los vectores de entrada prácticamente.
    
- **Tener unos buenos apuntes y una estructura clara en los procesos de ataque** va a ser crucial. Aquí hay que tratar de ser lo más eficientes y ahorrar la máxima cantidad de energía durante el examen. Tener esto claro te va a ahorrar mucho tiempo. Tratando este punto más en profundidad: tienes varias máquinas en el entorno, tener un foco bueno es decir, no pasar de una a la otra constantemente ni irse por las ramas.
    
- **Es un examen prácticamente de fuerza bruta.** Como menciono, el examen tiene una gran parte de fuerza bruta. Leer bien las preguntas y tener claro este punto. En mi caso, no encontraba los vectores de entrada y estaba pensando en cosas más complicadas de lo que realmente era.
    

**NO USAR LAS WORDLISTS DEL LETTER OF ENGAGEMENT.** Estas son las que mejor funcionan junto con el rockyou en algunas ocasiones:

- `/usr/share/seclists/Passwords/months.txt`
    
- `/usr/share/seclists/Passwords/seasons.txt`
    
- `/usr/share/seclists/Passwords/xato-net-10-million-passwords-1000000.txt`
    
- **Es un examen de AD pero puedes aprobar sin llegar a ser DOMAIN ADMIN.** Como digo, esto es real, pero aun así no hay que confiarse. Intentar contestar todas las preguntas y ir al 100%. No os confiéis o os puede pasar una mala jugada en el examen.
    
- **El entorno funciona mal.** Como el examen todavía es nuevo, puede ser un poco inestable. A veces las flags dinámicas no se inyectan correctamente en el entorno de examen, lo que hace que busques algo que no está en las máquinas. Por ejemplo, me pasó que una pregunta pedía encontrar un usuario específico en una máquina, pero el usuario no existía en ninguna hasta que reinicié el lab. Ten en cuenta que pueden haber estas inestabilidades.
    
- **No se puede utilizar `locate`.** Tenéis que usar `find`. La mayoría de herramientas están, pero no igual en el sitio que vosotros os pensáis o con el nombre.
    
- **Utilizar Metasploit.**
    

**Otros recursos:**

- [https://github.com/0xMat10/eCPPT_Prep](https://github.com/0xMat10/eCPPT_Prep)
    
- [https://dragkob.notion.site/ecpptv3-dragkob](https://dragkob.notion.site/ecpptv3-dragkob)
    
- [https://github.com/ant0sec/Methodology-eCPPT](https://github.com/ant0sec/Methodology-eCPPT)


# English

Review - eCPPTv3 INE Guide

Hello there. This will be a small guide with advice on how to approach the eCPPTv3 from INE.

My opinion:

First of all, I don't think it's a complicated exam, but you need a solid foundation and to know what you're doing. I consider the learning journey itself more important than the certification, as the certification will simply reflect the knowledge you've acquired.

It's not worth buying the $600 voucher with access to INE's training. I also don't think it's worth spending $400 for the standard voucher. In my case, all the INE certifications I have were purchased with a 50% discount (eJPT, eCPPT, and eWPT). I probably got all three for around $400 total. Otherwise, in my personal opinion, it's not worth it...

These guys usually release discounts every 3-4 months. In my case, I pinned the INE tab in my browser and checked it every day for several weeks.

My experience:

I've been in cybersecurity for just over a year, studying in my spare time while working. What I achieved could probably be done in much less time with proper optimization and a good roadmap. I've always studied on my own using HackTheBox and videos found on YouTube, but I believe that the content on the HackTheBox platform is largely responsible for where I am today.

Getting the student plan, which is about $10 per month, gives you access to a lot of high-quality, well-structured content. HackTheBox doesn't pay me to mention them; I'm just explaining my path to get here.

So, studying on my own, doing the HackTheBox paths, and getting the premium subscription to access the labs is how I learned. For about $25 you get the complete practice/theory pack. I bought the voucher for the eJPTv2 and passed it 4 months ago.

That means 4 months passed between the eJPT and the eCPPT, for various reasons, but you could likely make the jump in 1-2 months.

Resources:

HackTheBox Academy:
https://academy.hackthebox.com/module/details/143
It's worth paying for the module and going all in.

HackTheBox Labs:
https://app.hackthebox.com/
It's worth paying for VIP for a couple of months and going all in.

These are the machines I've done:

HACKMYVM
DC01
DC02
DC03
DC04

HACK THE BOX
MANAGER
ACTIVE
MONTEVERDE
RESOLUTE
SAUNA
FOREST
HOSPITAL
INTELLIGENCE
CICADA
HOSPITAL
HEIST
ADMINISTRATOR
RETURN
TIMELAPSE
JEEVES
CERTIFIED
JAB
STREAMIO

The HACKMYVM ones are completely free.

By doing these machines, having a solid foundation, and having completed the HackTheBox module, you will be more than prepared.

Things to keep in mind:

Read the questions very, very carefully and structure them. The questions are disordered; they don't follow a specific sequence, machine order, or anything like that. Reading and understanding them completely will save you a lot of time and effort. They will practically guide you through the path and the entry vectors.

Having good notes and a clear structure for your attack processes will be crucial. Here, you need to try to be as efficient as possible and conserve the maximum amount of energy during the exam. Being clear on this will save you a lot of time. Elaborating on this point: you have several machines in the environment, so maintaining good focus is key—meaning, don't constantly jump from one to another or go off on tangents.

It's practically a brute-force exam. As I mentioned, the exam has a significant brute-force component. Read the questions well and be clear on this point. In my case, I couldn't find the entry vectors and was overcomplicating things.

DO NOT USE THE WORDLISTS FROM THE LETTER OF ENGAGEMENT. These are the ones that work best, along with rockyou in some instances:

/usr/share/seclists/Passwords/months.txt

/usr/share/seclists/Passwords/seasons.txt

/usr/share/seclists/Passwords/xato-net-10-million-passwords-1000000.txt

It's an AD exam, but you can pass without becoming DOMAIN ADMIN. As I said, this is true, but even so, don't get overconfident. Try to answer all the questions and give it 100%. Don't get complacent, or it might backfire during the exam.

The lab environment can be faulty. Since the exam is still new, it can be somewhat unstable. Sometimes the dynamic flags are not injected correctly into the exam environment, leading you to search for something that isn't on the machines. For example, I encountered a question asking me to find a specific user on a machine, but the user didn't exist on any machine until I reset the lab. Be aware that these instabilities can occur.

You cannot use locate. You have to use find. Most tools are available, but not necessarily where you might expect or with the name you think.

Use Metasploit.

Other resources:

https://github.com/0xMat10/eCPPT_Prep

https://dragkob.notion.site/ecpptv3-dragkob

https://github.com/ant0sec/Methodology-eCPPT
