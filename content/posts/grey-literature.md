+++
date = '2026-07-25T20:06:23-04:00'
draft = false
title = 'Grey literature and where to find it'
+++
Did you know that almost every detail about the design and operation of a nuclear power plant is online? You can download it, for free, legally, from the Nuclear Regulatory Comission. Dont belive me? Have a look: [NRC ADAMS Search](https://adams-search.nrc.gov/home). This is just one example of "Grey Literature", defined as government, academic, or industry documents which are not published by a commercial publisher.

{{< figure
  src="/images/Containment_Building.png"
  alt="A cross-section of a nuclear containmennt building"
  caption="Elevation view of the containment building of a Westinghouse Pressurized Water Reactor, retreived from public NRC documents.  ([ML22334A221](https://www.nrc.gov/docs/ML1122/ML11223A221.pdf))"
  class="ma0 w-75 center"
>}}

There's a good chance you've already used grey literature. Technically, most datasheets fall under the definition, and application notes certainly do. But reading material companies publish with their products is only scratching the surface of grey literature. From building [space-rated wiring harnesses](https://s3vi.ndc.nasa.gov/ssri-kb/static/resources/nasa-std-8739.4a.pdf) to [marine cathodic protection](https://maritime.org/doc/pdf/ufc_3_570_02n.pdf) if there's some technical process you want to explore, chances the US government has published a manual on it.

The only question is, where do you find it?

# A lesson in Google-Fu

In the days of yore, getting access to this material as an individual was somewhat difficult. A company might have a library of datasheets and white papers, but the best an individual could do would be to explore the stacks of their local university library or get lucky at a used bookstore. These days, we are blessed with the internet and the Portable Document Format, and billions of documents are few keystrokes away. 

As is often the case, it's best to start with a search engine. Because most grey literature is online in the form of PDFs, restricting your search with `filetype:pdf` makes finding useful information slightly more likely. If you have an idea of who might puhblish material you're interested in, you can use `site:<their website>` to narrow the search. Sometimes, google doesn't cut it, so you must face the beast itself. Many technical agencies have databases of documents, such as the aforementioned NRC ADAMS or [the NASA Technical Reports Server](https://ntrs.nasa.gov/). In theory these databases have search tools, but they're not always easy to use. I reccomend using a combination of conventional search engines and database searches.

Here is a list of particularly useful peices of grey literature I've found for my work. 

- [LIGO Vacuum Compatible Materials](https://dcc-llo.ligo.org/public/0003/E960050/011/E960050-v11%20Vacuum%20Compatible%20Materials%20List.pdf) This is the bible for high vacuum materials selection. If we're considering putting a new material into the chamber at work, we look it up here first.
- [Human Factors for Nuclear Control Room Design](https://www.osti.gov/servlets/purl/5303070) When desigining human-machine interfaces, this is the document I reference. It's a little bit outdated, and focuses on physical gauges as opposed to a control interface on a screen, but it's still one of the best ergonomics documents out there.
- [Handbook of Operational Amplifier Applications](https://www.ti.com/lit/an/sboa092b/sboa092b.pdf): This one's a classic to people in the electronics space. I'm pretty sure I heard about it on the [EEVblog Forum](https://www.eevblog.com/forum/). It's basically every op-amp circuit you'd ever want in one place. 
- [Stanford Research Systems Manuals](https://www.thinksrs.com/downloads/man.html): I heard about this one from the folks at the SRS booth at the 2026 APS summit. SRS is kind enough to publish complete component level schematics of all of their instruments in their manuals. I've yet to borrow any circuits from them, but I really appreciate their technical openness in this age of propreitary everything. 


