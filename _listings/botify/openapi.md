swagger: "2.0"
x-collection-name: Botify
x-complete: 1
info:
  title: Botify
  description: botify-saas-api
  version: 1.0.0
host: api.botify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /analyses/{username}/{project_slug}:
    parameters:
      summary: Parameters Analyses Username Project Slug
      description: Parameters analyses username project slug.
      operationId: parametersAnalysesUsernameProjectSlug
      x-api-path-slug: analysesusernameproject-slug-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
  /analyses/{username}/{project_slug}/{analysis_slug}:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug
      description: Parameters analyses username project slug analysis slug.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlug
      x-api-path-slug: analysesusernameproject-sluganalysis-slug-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
  /analyses/{username}/{project_slug}/{analysis_slug}/crawl_statistics:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Crawl Statistics
      description: Parameters analyses username project slug analysis slug crawl statistics.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugCrawlStatistics
      x-api-path-slug: analysesusernameproject-sluganalysis-slugcrawl-statistics-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Crawl
      - Statistics
  /analyses/{username}/{project_slug}/{analysis_slug}/crawl_statistics/time:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Crawl Statistics
        Time
      description: Parameters analyses username project slug analysis slug crawl statistics
        time.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugCrawlStatisticsTime
      x-api-path-slug: analysesusernameproject-sluganalysis-slugcrawl-statisticstime-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Crawl
      - Statistics
      - Time
  /analyses/{username}/{project_slug}/{analysis_slug}/crawl_statistics/urls/{list_type}:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Crawl Statistics
        Urls List Type
      description: Parameters analyses username project slug analysis slug crawl statistics
        urls list type.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugCrawlStatisticsUrlsListType
      x-api-path-slug: analysesusernameproject-sluganalysis-slugcrawl-statisticsurlslist-type-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Crawl
      - Statistics
      - Urls
      - List
      - Type
  /analyses/{username}/{project_slug}/{analysis_slug}/features/ganalytics/orphan_urls/{medium}/{source}:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Ganalytics
        Orphan Urls Medium Source
      description: Parameters analyses username project slug analysis slug features
        ganalytics orphan urls medium source.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesGanalyticsOrphanUrlsMediumSource
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturesganalyticsorphan-urlsmediumsource-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Ganalytics
      - Orphan
      - Urls
      - Medium
      - Source
  /analyses/{username}/{project_slug}/{analysis_slug}/features/links/percentiles:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Links
        Percentiles
      description: Parameters analyses username project slug analysis slug features
        links percentiles.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesLinksPercentiles
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeatureslinkspercentiles-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Links
      - Percentiles
  /analyses/{username}/{project_slug}/{analysis_slug}/features/pagerank/lost:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Pagerank
        Lost
      description: Parameters analyses username project slug analysis slug features
        pagerank lost.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesPagerankLost
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturespageranklost-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Pagerank
      - Lost
  /analyses/{username}/{project_slug}/{analysis_slug}/features/sitemaps/report:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Sitemaps
        Report
      description: Parameters analyses username project slug analysis slug features
        sitemaps report.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesSitemapsReport
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturessitemapsreport-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Sitemaps
      - Report
  /analyses/{username}/{project_slug}/{analysis_slug}/features/sitemaps/samples/out_of_config:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Sitemaps
        Samples Out Of Config
      description: Parameters analyses username project slug analysis slug features
        sitemaps samples out of config.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesSitemapsSamplesOutOfConfig
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturessitemapssamplesout-of-config-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Sitemaps
      - Samples
      - Out
      - Of
      - Config
  /analyses/{username}/{project_slug}/{analysis_slug}/features/sitemaps/samples/sitemap_only:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Sitemaps
        Samples Sitemap Only
      description: Parameters analyses username project slug analysis slug features
        sitemaps samples sitemap only.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesSitemapsSamplesSitemapOnly
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturessitemapssamplessitemap-only-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Sitemaps
      - Samples
      - Sitemap
      - Only
  /analyses/{username}/{project_slug}/{analysis_slug}/features/top_domains/domains:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Top
        Domains Domains
      description: Parameters analyses username project slug analysis slug features
        top domains domains.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesTopDomainsDomains
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturestop-domainsdomains-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Top
      - Domains
      - Domains
  /analyses/{username}/{project_slug}/{analysis_slug}/features/top_domains/subdomains:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Top
        Domains Subdomains
      description: Parameters analyses username project slug analysis slug features
        top domains subdomains.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesTopDomainsSubdomains
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturestop-domainssubdomains-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Top
      - Domains
      - Subdomains
  /analyses/{username}/{project_slug}/{analysis_slug}/features/visits/orphan_urls/{medium}/{source}:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Features Visits
        Orphan Urls Medium Source
      description: Parameters analyses username project slug analysis slug features
        visits orphan urls medium source.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugFeaturesVisitsOrphanUrlsMediumSource
      x-api-path-slug: analysesusernameproject-sluganalysis-slugfeaturesvisitsorphan-urlsmediumsource-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Features
      - Visits
      - Orphan
      - Urls
      - Medium
      - Source
  /analyses/{username}/{project_slug}/{analysis_slug}/urls:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Urls
      description: Parameters analyses username project slug analysis slug urls.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugUrls
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurls-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
  /analyses/{username}/{project_slug}/{analysis_slug}/urls/aggs:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Urls Aggs
      description: Parameters analyses username project slug analysis slug urls aggs.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugUrlsAggs
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurlsaggs-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
      - Aggs
  /analyses/{username}/{project_slug}/{analysis_slug}/urls/datamodel:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Urls Datamodel
      description: Parameters analyses username project slug analysis slug urls datamodel.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugUrlsDatamodel
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurlsdatamodel-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
      - Datamodel
  /analyses/{username}/{project_slug}/{analysis_slug}/urls/export:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Urls Export
      description: Parameters analyses username project slug analysis slug urls export.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugUrlsExport
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurlsexport-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
      - Export
  /analyses/{username}/{project_slug}/{analysis_slug}/urls/export/{url_export_id}:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Urls Export
        Url Export
      description: Parameters analyses username project slug analysis slug urls export
        url export.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugUrlsExportUrlExport
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurlsexporturl-export-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
      - Export
      - Url
      - Export
      - Id
  /analyses/{username}/{project_slug}/{analysis_slug}/urls/suggested_filters:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Urls Suggested
        Filters
      description: Parameters analyses username project slug analysis slug urls suggested
        filters.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugUrlsSuggestedFilters
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurlssuggested-filters-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
      - Suggested
      - Filters
  /analyses/{username}/{project_slug}/{analysis_slug}/urls/{url}:
    parameters:
      summary: Parameters Analyses Username Project Slug Analysis Slug Urls Url
      description: Parameters analyses username project slug analysis slug urls url.
      operationId: parametersAnalysesUsernameProjectSlugAnalysisSlugUrlsUrl
      x-api-path-slug: analysesusernameproject-sluganalysis-slugurlsurl-parameters
      responses:
        200:
          description: OK
      tags:
      - Analyses
      - Username
      - Project
      - Slug
      - Analysis
      - Slug
      - Urls
      - Url