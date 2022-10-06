# What is this?
This is the ~~first~~ *second* iteration of my personal site which is written in HTML and uses minimal backend (for the time being). The goal of this project is to make a consistant web app which is small enough to run off a floppy disk.

Eventually, I will be implementing actual scripts and such to make this run smoother and look better, as well as SSL certificates and overall better design. The first version of this is basically just some HTML and a few lines of CSS to pretty it up.

This repo is the working repository for this project. All changes made here will eventually be reflected on the actual site after they are tested and verified. The whole system is essentially air gapped from unintentional errors due to the nature of Github development and local storage.

All images are either made by me or taken from a Win 9X system. Most images are hosted through Imgur, as to minimize storage requirments.

# Updates
I initially intended for this entire site to be run off a first gen raspberry pi and floppy disk. The site was very barebones to account for that. I have made the decision to migrate away from that quirky appearance due to the inefficiency and inconvenience of the system. I plan to rebuild the entire thing when I have the time (so in the next 20 years *maybe*) in React. I have a UX design I want to implement and I am currently learning JS so I feel like it will be a welcome change.

The site has SSL and protection against crawlers now. I really like the https:// in front of it. It makes me feel like I’m smart in a weird way.  This was impossible on the ARM5 processor, so I upgraded to a Pi 3B. I plan on possibly moving my operation to primary server, and running it in a docker container. Honestly though, once I can, I might move it to an AWS server and update it with amplify. I love self hosting, but my ISP changes my IP frequently so I would prefer to have something more stable. Regardless, the future is bright for this site, and hopefully the next build of it is good enough to get its own separate repo.
