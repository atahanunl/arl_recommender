# Association Rule Based Recommender System

## Business Problem

Armut, recognized as Turkey's foremost online service platform, serves as a nexus connecting service providers with
those in need. It streamlines access to services such as cleaning, renovation, and moving through a simple interface on
computers or smartphones. The intention is to employ Association Rule Learning to develop a product recommendation
system based on the dataset encompassing users who have availed services and the corresponding service categories.

## Dataset Story

The dataset comprises information about the services customers have acquired and the respective service categories.
Additionally, it includes the date and time details for each service received.

## Features

- `UserId` - Distinct customer identifier
- `ServiceId` - Anonymized services associated with each category. For instance, within the cleaning category, a service
  could be upholstery cleaning. `ServiceId` may appear across different categories, signifying diverse services under
  distinct categories or a service with `CategoryId` = 7 and `ServiceId` = 4 could be radiator cleaning, whereas a
  service with `CategoryId` = 2 and `ServiceId` = 4 might be furniture assembly
- `CategoryId` - Anonymized categories. For instance; cleaning, moving, renovation
- `CreateDate` - The date on which the service was purchased