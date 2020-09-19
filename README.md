### Interesting Stuff

[Trends in AirBnB by area](https://www.airdna.co/vacation-rental-data/app/jp/hiroshima-ken/naka-ku/overview)

[All Kinds of APIs](https://rapidapi.com/category/Travel)

[Economy, Sentiment, and Movement Dashboard](https://www2.deloitte.com/ca/en/pages/about-deloitte/articles/covid-dashboard.html?is=5e8d4f149b0f225dde35ccbe)


<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
        <meta name="theme-color" content="#000000" />
        <title>The New WashU Epigenome Browser</title>
        <link
            rel="stylesheet"
            href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
            integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm"
            crossorigin="anonymous"
        />
        <script src="https://igv.org/web/release/2.0.1/dist/igv.min.js"></script>
        <script src="https://igv.org/web/jb/release/1.0.0/dist/juicebox.min.js"></script>
        <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
        <script
            src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
            integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
            crossorigin="anonymous"
        ></script>
        <script
            src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
            integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
            crossorigin="anonymous"
        ></script>
        <script
            src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
            integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
            crossorigin="anonymous"
        ></script>
        <script src="https://target.wustl.edu/dli/eg/epgg.js"></script>
        <link rel="stylesheet" href="https://unpkg.com/epgg@latest/umd/epgg.css" />
    </head>
    <body>
        <noscript>
            You need to enable JavaScript to run this app.
        </noscript>
        <h1>Embedding test</h1>
        <div id="embed" style="width:1000px"></div>
        <h2>some other headings</h2>
        <script>
            const container = document.getElementById("embed");
            const contents = {
                genomeName: "mm10",
                displayRegion: "chr5:51997494-52853744",
                trackLegendWidth: 120,
                isShowingNavigator: true,
                tracks: [
                    {
                        type: "geneannotation",
                        name: "refGene",
                        genome: "mm10",
                    },
                    {
                        type: "geneannotation",
                        name: "gencodeM19Basic",
                        genome: "mm10",
                    },
                    {
                        type: "ruler",
                        name: "Ruler",
                    },
                    {
                        type: "bigWig",
                        name: "ChipSeq of Heart",
                        url: "https://www.encodeproject.org/files/ENCFF641FBI/@@download/ENCFF641FBI.bigWig",
                        options: { color: "red" },
                        metadata: { Sample: "Heart" },
                    },
                    {
                        type: "bigWig",
                        name: "ChipSeq of Liver",
                        url: "https://www.encodeproject.org/files/ENCFF555LBI/@@download/ENCFF555LBI.bigWig",
                        options: { color: "blue" },
                        metadata: { Sample: "Liver" },
                    },
                ],
                metadataTerms: ["Sample"],
                regionSets: [],
                regionSetViewIndex: -1,
            };
            renderBrowserInElement(contents, container);
        </script>
    </body>
</html>

[I See You](https://www.shodan.io/search?query=ver2.4+rev0+country%3A%22JP%22+has_screenshot%3Atrue)
