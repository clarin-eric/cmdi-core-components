## Core components and use case profiles
Last update: 20 September 2021, 9:38 CEST

### Profiles
-   [ADP-DDI](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1595321762428)
-   [Virtual Collection Registry](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1595321762407/xsd) (too big to load for now? sorry...)
-   [DataCiteRecord](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1610707853541) `NEW`
    -   Conversion use case
    -   Conversion from native DataCite XML: [implementation](https://github.com/clarin-eric/metadata-conversion/tree/datacite-cmdi/datacite-cmdi), [example records in Alpha VLO](https://alpha-vlo.clarin.eu/?fqType=dataProvider:or&fq=dataProvider:DataCite+-+CMDI+conversion+test)
-   [LCR_Corpus](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1610707853542) `NEW` (too big to load for now? sorry...)
    -   Profile for Learner Corpus Research (non-conversion use case)

### Components

#### "Entity components"

Repeatable items that can have an identifier, a label and additional properties

-   [Contributor](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762453) `UPDATED`
-   [Country](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762419) `UPDATED`
-   [Creator](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762404) `UPDATED`
-   [Licence](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762457) `NEW`
-   [GeoLocation](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762418) `UPDATED`
-   [Keyword](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762456)
-   [Language](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762414)
-   [Publisher](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762427)
-   [RelatedResource](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762430) `UPDATED`
-   [ResourceType](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762403)
-   [Subject](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762455) `UPDATED`
-   [Subresource](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762415)
-   [TemporalCoverage](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762417)

#### "Information grouping components"

Named `*-Info` or `*-Description`

(Description is typically repeatable, info is not)

-   [AccessInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762454)
-   [ActivityInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762422) `UPDATED`
-   [AgentInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762451)
-   [CitationInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762416) 
-   [ContactInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762406) `UPDATED`
-   [Description](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762411)
-   [FundingInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762429)
-   [IdentificationInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762421) `UPDATED`
-   [MetadataInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762458)
-   [OrganisationInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762452) `UPDATED`
-   [PersonInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762426) `UPDATED`
-   [ProvenanceInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762423) `UPDATED`
-   [SubresourceDescription](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762413)
-   [SubresourceTechnicalInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762405) `UPDATED`
-   [TitleInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762412)
-   [VersionInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762424)
