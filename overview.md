## Core components and use case profiles
Last update: 10 May 2022, 10:50 CEST

### Profiles
-   [DDICodebook](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1595321762428)
    -   Conversion use case
-   [DataCiteRecord](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1610707853541)
    -   Conversion use case
    -   Conversion from native DataCite XML: [implementation](https://github.com/clarin-eric/metadata-conversion/tree/datacite-cmdi/datacite-cmdi)
    -   New: [Records in the VLO!](https://vlo.clarin.eu/search?q=_componentProfileId:clarin.eu:cr1:p_1610707853541)
-   [MetadataCollection](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1639731773869) `NEW`
    - [Records in the VLO!](https://vlo.clarin.eu/search?q=_componentProfileId:clarin.eu:cr1:p_1639731773869)
-   [TextResource](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1633000337997) `NEW`
    - [Records in the VLO!](https://vlo.clarin.eu/search?q=_componentProfileId:clarin.eu:cr1:p_1633000337997)
-   [LCR_Corpus](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1610707853542) (work in progress, please do not use yet)
    -   Profile for Learner Corpus Research (non-conversion use case)
-   [Virtual Collection Registry](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:p_1595321762407/xsd) (too big to load for now? sorry...)

### Components

#### "Entity components"

Repeatable items that can have an identifier, a label and additional properties

-   [Contributor](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762453)
-   [Country](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762419)
-   [Creator](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762404)
-   [Licence](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762457)
-   [GeoLocation](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762418)
-   [Keyword](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762456)
-   [Language](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762414)
-   [Publisher](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762427)
-   [RelatedResource](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762430)
-   [ResourceType](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762403)
-   [Subject](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762455)
-   [Subresource](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762415) `UPDATED`
-   [TemporalCoverage](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762417) `UPDATED`

#### "Information grouping components"

Named `*-Info` or `*-Description`

(Description is typically repeatable, info is not)

-   [AccessInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762454)
-   [ActivityInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762422)
-   [AgentInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762451)
-   [CitationInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762416) 
-   [ContactInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762406)
-   [Description](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762411)
-   [FundingInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762429)
-   [IdentificationInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762421)
-   [MetadataInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762458)
-   [OrganisationInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762452)
-   [PersonInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762426)
-   [ProvenanceInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762423)
-   [SubresourceDescription](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762413) `UPDATED`
-   [SubresourceTechnicalInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762405)
-   [TitleInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762412)
-   [VersionInfo](https://menzowindhouwer.github.io/lab/cr2html/index.html#clarin.eu:cr1:c_1595321762424)
