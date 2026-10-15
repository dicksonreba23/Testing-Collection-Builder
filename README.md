# DSG Template: CollectionBuilder-Sheets

This CollectionBuilder-Sheets is a template for creating simple digital exhibit websites by loading collection metadata directly from a CSV (such as a published Google Sheet!). 
This enables live collaboration to prototype collections with minimal set up.
This is the Digital Scholarship Group's teaching template for using CollectionBuilder-Sheets.
Driven by your collection metadata, the template generates engaging visualizations to browse and explore your objects.
The resulting static site can be hosted on any basic web server (*or built automatically and hosted for free on GitHub Pages!*).

Visit the [CB-Sheets demo site](https://collectionbuilder.github.io/collectionbuilder-sheets/) to see it in action and even test your own metadata!

To learn more check [docs/sheets-metadata.md](docs/sheets-metadata.md) or visit the [CollectionBuilder Docs](https://collectionbuilder.github.io/cb-docs/) for step-by-step details for getting started and building collections.

Note that CB-Sheets is based on and mostly compatible with [CollectionBuilder-GH](https://github.com/CollectionBuilder/collectionbuilder-gh), but handles the metadata parsing in a fundamentally different way. 

If developing CB-Sheets on your local machine, use Ruby 3.4.x (Ruby 4 does not work with the `github-pages` gem) or check the "Gemfile" comments for options.

## DSG Workshop Metadata Information

### Roxbury Mural Information
#### FacesOfDudley_JermaineGC_1.jpg
Title:  Faces of Dudley	1 \
Creator: Mayors Mural Crew, Mike Womble	Jermaine G-C	Boston Research Center, ICA Teen Photography Collection \
Date: 7/8/2025 \
Type of resource: born digital image \
Abstract/description: A mural painted with acrylics in Dudley Square, directed by Mike Womble of the Mayor's Mural Crew along with a group of teen artists in 1995. It displays various Roxbury features, such as a train station, small businesses such as a barbershop, a basketball hoop, light posts, and faces of Roxbury residents. Among the people depicted are Malcolm X, Melnea Cass, and Elma Lewis. This is the only one of three murals painted by the Mayor's Mural Crew in Dudley Square that has not yet been demolished. \
Subject: Public art; Roxbury, MA
#### FacesOfDudley_JermaineGC_3.jpg
Title:  Faces of Dudley	3 \
Creator: Mayors Mural Crew, Mike Womble	Jermaine G-C	Boston Research Center, ICA Teen Photography Collection \
Date: 7/8/2025 \
Type of resource: born digital image \	
Abstract/description: A mural painted with acrylics in Dudley Square, directed by Mike Womble of the Mayor's Mural Crew along with a group of teen artists in 1995. It displays various Roxbury features, such as a train station, small businesses such as a barbershop, a basketball hoop, light posts, and faces of Roxbury residents. Among the people depicted are Malcolm X, Melnea Cass, and Elma Lewis. This is the only one of three murals painted by the Mayor's Mural Crew in Dudley Square that has not yet been demolished. \
Subject: Public art; Roxbury, MA
### Queen of Disco Mural Information
Title: Queen of Disco \
Creator: Cedric "Vise1" Douglas	(Artist), Brianna B (Photographer), Boston Research Center, ICA Teen Photography Collection \
Date created: 7/8/2025 \
Abstract/description: a mural of Donna Summer located in Roxbury, Massachusetts \
Type of resource: born digital image \
Subject: Public art; Roxbury, MA; Donna Summer


### Everybody Wants a Piece of East Boston


  Title: Transcript of 'Everybody Wants a Piece of East Boston' (English) \
Creator: MacDonald, Christine (Editor), Peralta Torres , Claudia (Editor), Boston Research Center, Hola Cultura \
Date created: January 2025 \
Type of resource: Text \
Abstract/Description: English language transcript of the recording 'Everybody Wants a Piece of East Boston.' "Everybody wants a piece of East Boston," Eva Biscegli observed in an oral history interview recorded in the late 1990s. Decades later, as developers move in, those words still ring true. But adversity has bred generations of committed resident activists and big successes over the years - like stopping Boston Logan International Airport's expansion in the 1970s and banding together to provide mutual aid during the COVID-19 pandemic. Journalist Renée Loth reminisces about the East Boston Community News (1970-1989) while Chris Marchi of Air Inc.; Liliana Tirado Arteaga of Mothers Out Front; and Eastie Farm's Kannan Thiruvengadam discuss the neighborhood today. \
Subjects and keywords: East Boston History, Environmental justice, COVID-19 (Disease), Community organization \

  Title: Transcript of 'Everybody Wants a Piece of East Boston' (Spanish) \
  Creator: MacDonald, Christine (Scriptwriter), Peralta Torres, Claudia (Scriptwriter, Audio editor),Boston Research Center, Hola Cultura \
  Date created: January 2025 \
  Type of resource: Text \
  Format: Video \
  Abstract/Description: "Everybody wants a piece of East Boston," Eva Biscegli observed in an oral history interview recorded in the late 1990s. Decades later, as developers move in, those words still ring true. But adversity has bred generations of committed resident activists and big successes over the years - like stopping Boston Logan International Airport's expansion in the 1970s and banding together to provide mutual aid during the COVID-19 pandemic. Journalist   Renée Loth reminisces about the East Boston Community News (1970-1989) while Chris Marchi of Air Inc.; Liliana Tirado Arteaga of Mothers Out Front; and Eastie Farm's Kannan Thiruvengadam discuss the neighborhood today. \
  Subjects and keywords: East Boston History, Environmental justice, COVID-19 (Disease), Community organization \



## CollectionBuilder 

<https://collectionbuilder.github.io/>

CollectionBuilder is a project of University of Idaho Library's [Digital Initiatives](https://www.lib.uidaho.edu/digital/) and the [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu) (CDIL) following the [Lib-Static](https://lib-static.github.io/) methodology. 
Powered by the open source static site generator [Jekyll](https://jekyllrb.com/) and a modern static web stack, it puts collection metadata to work building beautiful sites.

The basic theme is created using [Bootstrap](https://getbootstrap.com/).
Metadata visualizations are built using open source libraries such as [DataTables](https://datatables.net/), [Leafletjs](http://leafletjs.com/), [Spotlight gallery](https://github.com/nextapps-de/spotlight), [lazysizes](https://github.com/aFarkas/lazysizes), and [Lunr.js](https://lunrjs.com/).
Object metadata is exposed using [Schema.org](http://schema.org) and [Open Graph protocol](http://ogp.me/) standards.

Questions can be directed to **collectionbuilder.team@gmail.com**

## License

CollectionBuilder documentation and general web content is licensed [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/). 
This license does *NOT* include any objects or images used in digital collections, which may have individually applied licenses described by a "rights" field.
CollectionBuilder code is licensed [MIT](https://github.com/CollectionBuilder/collectionbuilder-gh/blob/main/LICENSE). 
This license does not include external dependencies included in the `assets/lib` directory, which are covered by their individual licenses.
