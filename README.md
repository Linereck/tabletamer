# tabletamer
A tool to identify, standardize, and export complex tabular data from scientific papers to facilitate use by other tools, formats, and applications.

## Background:
Scientific papers often contain complex tabular data related to the pharmacological activities, uses, and effects of drugs, plant extracts, and their chemical constituents. This data includes Minimum Effective Concentrations, Maximum Safe Concentrations, and toxicity measurements, as well as information on plant names, extract types, extraction methods, and the concentration of each detected chemical constituent. 

However, there is no standardized method for displaying this data, making it difficult to extract and use for knowledge transfer.

The big challenge to using this data (from hundreds of thousands of papers) is that no single set standard exists for how the papers’ authors display their data in their papers. They can often combine different types of data, which should be separated, in the same table. Or they’ll display the data for many tested plants in the same table… some with their own columns of data, and sometimes with their own horizontal “sections” in rows of data. All of this makes data extraction (let alone knowledge extraction) an very difficult task. Currently no available tool can do this without human intervention, and because of the number of papers involved and the variations of “deciphering” that will be needed, finding enough humans to do this accurately and cost-efficiently is next to impossible. Add to this the impediment of needing to extract, interpret and normalize that data from PDFs, as opposed to any machine-readable format such as XML, makes this task currently impossible.

## Our Purpose:
The purpose of this project is to develop a tool that can identify, standardize, and export complex tabular data from scientific papers, starting with PDF and XML formats. This will enable the efficient transfer of knowledge to other tools and applications.