---
layout: blank
---
<GalleryCarousel :depiction-id= "[708197]" height="500px">
  <div class="flex flex-col justify-center items-center w-full h-full bg-black bg-opacity-25 text-white gap-4 px-4 box-border">
    <span class="text-4xl font-medium">{{ app:project_name }}</span>
    <p class="text-lg sm:text-xl">A virtual catalog of fungus weevil species</p>
    <div class="mx-auto flex flex-col items-center mt-6 sm:mt-10 w-full ">
      <autocomplete-otu class="w-full sm:w-96 text-base-content ml-2 sm:ml-0" placeholder="Search by taxon name" autofocus/>
    </em>
    </div>
  </div>
</GalleryCarousel>    

<div class="container mx-auto my-8 px-4 md:px-0 box-border">
  
# {{frontmatter.title}}
_{{frontmatter.lead}}_

## Overview
Welcome to *{{ frontmatter.project }}*, a website of taxon pages generated from the {{ frontmatter.project }} Project managed in [TaxonWorks](https://taxonworks.org). Records and images are obtained from various sources including active digitization of the [ASU Biocollections](https://sols.asu.edu/research/natural-history-collections) on [ecdysis](https://ecdysis.org), as well as occurrences mobilized to [GBIF](https://gbif.org) by several institutions. 

## Search Anthribidae
<autocomplete-otu class="w-80"/>

## Announcements
* 10/25/2023 - Our website is live!
