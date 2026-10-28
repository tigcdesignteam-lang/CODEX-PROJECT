# Final Canva range update — 44 colourways

Updated against the user-supplied 19-page PRODUCT POLO compressed PDF.

- [Updated Excel with final renders and colour names](Fabric_Style_Dashboard_Final.xlsx)
- [Labelled final PDF](PRODUCT_POLO_Colour_Names.pdf)
- [Canva-importable presentation with editable colour-name labels](PRODUCT_POLO_Colour_Names_Canva.pptx)
- [Colourway list and counts (CSV)](Colourway_Summary.csv)

Open a file on GitHub and choose **Download raw file**. Import the PowerPoint into Canva to use the labelled presentation. The live Canva design has not been edited.

## Verified range

19 designs, 44 colourways. PDF pages 6 and 7 each contain five colourways; page 10 contains three; page 11 contains one colourway shown front/back with badge detail; all other pages contain two. Colour names match across Excel, PDF, presentation and CSV.

The Excel has been simplified as requested: only the former Sheet-02, Style Catalog, remains. It contains 44 colourway rows and 44 final render images. Style Description, Source PDF Page, Style Colourway Count, Colourway Position, Colour Name Source, Changes / Notes, Final Back, Final Detail, and Original J Value (unit unspecified) columns were removed. All other workbook sheets, including Read Me, were deleted.

## Style mapping

Existing IDs are preserved by matching garment designs. ST-08 essential crew is PDF page 6, expanded to five colourways. The new contrast-collar polo on page 7 is ST-20. ST-07 chest-block polo is page 8. ST-06 mustard henley is absent from the final PDF and the final catalogue.

The final PDF supersedes earlier render concepts, including ST-11's back graphic placement and V neckline, ST-14/15 palettes, and ST-18/19 fabric labels. Other than source-embedded names, colour names are descriptive visual identifications, not certified supplier shade codes. Source compression limits render resolution.

A Quantity column contains 400 for each of the 44 colourway rows, as requested (17,600 total).

## Pantone references — revised from the image pixels

The earlier colour-name-based Pantone proposals have been replaced with **approximate image-based digital matches** after user review. [Download the garment/sample/reference comparison PDF](Pantone_Visual_Comparison.pdf), and [part-by-part reference CSV](Pantone_References_By_Colour.csv).

The single-sheet Excel retains 44 colourways, their 44 original final-render images, and Quantity 400 in every row. It now includes sampled-image swatches, proposed digital TCX references and TCX screen swatches alongside each garment. Thin white/blue pinstripes also visible on ST-12 are included in the component audit.

Fabric-region pixels were selected from the final PDF render crops using local medians and separate stripe/embroidery masks; skin, background and obvious shadows were checked visually. Sample coordinates and selectors are in the CSV and cell comments. The closest reference is computed using sRGB to CIELAB D65 and CIEDE2000; the implementation passes the three stated Sharma reference test pairs. The digital reference data is [pantone-tcx 2.2.4](https://www.npmjs.com/package/pantone-tcx) ([source](https://github.com/pedroduke/pantone-tcx), ISC licence), a third-party RGB dataset, not an official Pantone measurement or certification.

**Every match is approximate.** The comparison is between image pixels and listed RGB approximations of TCX colours. It cannot recover the intended physical yarn shade, correct unknown lighting/white balance, or certify a production match. Screen deltaE00 values are not physical colour tolerances. Very small micro-stripes and embroidery are especially uncertain in the compressed PDF. Repeated generic colour names can produce different digital proposals in differently lit renders.

Original numbers printed in the supplied PDF are retained separately in the CSV when previously transcribed; they do not automatically override the visual match. The two unlocated PDF labels (Eucalyptus 19-0223 and Earthy Brown 19-2421) remain unverified source information.

Approve every colour using a current physical Pantone FHI TCX cotton standard and an actual yarn/knit lab dip before production. The existing labelled Canva-importable deck has not been modified with these approximate references.
