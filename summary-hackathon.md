## Summary of the protocol hackathon

On monday/tuesday I organized a hackathon in our lab, which was suppose to digitalize large parts of our protocols and upload them to the open access platform [protocols.io](www.protocols.io). I also wanted to test the platform with all its features. I think the hackathon was an overall success with 8 new users, 30 uploaded protocols, and 8 that are openly shared. The rest will follow but they need some improvements before we do it. I hope that we continue to upload our protocols and start using the platform not only as an open storage for protocols but also for its ease the run a protocol. During the process of creating new protocols, we came across some inconveniences/issues and ideas for improvements that I want to share here.

### Inconveniences/Issues

__Log in with Google ID or similar__

If you log in to protocols.io with your Google ID or similar, the log in window won't close automaticly after a successful log in. You need to refresh the website in order to log in. However, if you use a normal mail plus password combination, it works nicely. We tested this with Google Chrome (Windows + Mac) and Safari (Mac).

__Mobile app__

Inconveniences/Issues with the mobile app:

1. Not all of the protocols, you created or are shared with you, show up under "My Protocols".
2. A group tab would be great. Right now there is no way to access your groups.

__Groups__

We wanted to use the group function as a way to collect all of our protocols, including protocols from companies. This is only possible if you fork a certain protocol and then share it in the group. It would be great if you could share bookmarks within a group or that group admins can make bookmark for that group.

__Collections__

If you want to create a collection, you need to own the protocol, i.e. created or forked by you. So I cannot make a collection of protocols shared with me, which is usually the case with groups. For a lab that would mean that a single person needs to own all protocols. We created a central account that anyone can use beside his/her private account. This is a little bit inconveniened. It would therefore be good that at least all group members have access to the protocols. Furthermore one could think about including protocols that are shared with you, bookmarks, or just all protocols for creating a collection. Collections should be something like a folder of protocols for a certain topic.

__Protocols__

Inconveniences/Issues with Protocols:

1. Is there a difference between tags and keywords? You can add both to the protocol extras, but I don't see the difference, or I don't know what keywords actually do. Tags show up in the protocol.
2. It would be great if you could add multiple entities of one tool, i.e. timer or reagent, to a single step. I think to only thing that should stay at one entity is a protocol.
3. Futher you can not link protocols that already link a protocol. So nested protocols are only possible for one protocol.
4. Can you create a template for affiliation etc.? Maybe create for the "Authors" selction a function to include profiles, like for sharing, not only names. This will then add the affiliations that is provided by the profile.
5. When you upload a protocol, you have to pick a group and press "+" before you can share it. The "+" is one additional click that is not intuitive and could be removed.
6. After you shared a protocol with the group, the window will not close by itself.
7. A download format in JATS XML format would be an awesome feature. It is a standard format used by journals and it is machine readable. The API would benefit from it.
8. How do contributions show up on ORCID?

__Automatic upload of protocols__

Apparently protcols.io is building parser to automaticly upload protocols from PDF or Word file. I think this is a crazy project, if you think about all these non standard protocols you would get. I think it would be helpful to provide a template, so that the parser has some standards to work with. I tried to provide a template for the lab, but it seems that almost every single protocols needs an additional table here and can delete one over there. So this is already a hard taks to do. Maybe an automatic web scraping of OpenWetWare protocols would be a better idea to start with.

### Comparison to other platforms

We didn't get to the point of comparing protocol.io with other platforms, because we didn't have experience with other platforms and no time. But I think it is worth doing it in the future. Maybe there is already such a comparison out there that I'm not aware of.

List of other platforms:

* [addgene](https://www.addgene.org) (Plasmid Repository)
* [OpenWetWare Wiki](http://www.openwetware.org/wiki/Protocols)
* [Nature Protocol Exchange](http://www.nature.com/protocolexchange/)
* [Protocol Online](http://www.protocol-online.org)
* [LabGuru](https://www.labguru.com) (Lab Management Platform)
* [Quartyz](https://www.quartzy.com) (Lab Management Platform)

I think protocols.io bets some of these alternatives with: its broad usage, open access, mobile app, nice UI, DOI protection. (Just by short skimming through the webpage of the other platforms. Might be wrong.) I think an integration of protocols.io into lab management platorms or digital lab journals would be great.

### Integration into other platforms

More and more people use lab management platforms such as LabGuru, or write digital lab notebooks on platforms like [labfolder](https://www.labfolder.com), [open science framework](https://osf.io), or [benchling](https://benchling.com). An integration of protocols.io in such platforms would be awesome, so you can have everything in one place. You could simply link the protocol your using, but running it in the notebook would simplify it.


### Conclusion

Even though we found some issues with protocols.io, I think it is a fabulous tool for any wetlab researcher. Highly recommended.

-- Cheers, Nic
