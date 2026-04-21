# IDSA Glossary

This draft document is created to ensure consistent terminology across IDSA's documents.
The definitions are aligned with the ISO DIS 20151 (to be published at the time of writing this document) and the Dataspace Protocol (2025-1 release) where possible.
Additional notes are provided where different terms are used for the same concept across the two sources.
Please note this is just an initial draft to provide a starting point. The structure and approach could be updated in the next steps.

## A

### Agreement

A concrete [Policy](#policy) associated with a specific [Dataset](#dataset) that has been agreed between the [Provider](#provider) and [Consumer](#consumer). It is a result of a [Contract Negotiation](#contract-negotiation) defining the [Policy](#policy) agreed to for a [Dataset](#dataset).
Please also see [data sharing contract]

(Source: ISO/IEC DIS 20151)

## C

### Catalog

A collection of entries representing [Offers](#offer) that are advertised by a [Provider](#provider).

(Source: Dataspace Protocol)

### Catalog Protocol

A set of allowable [Message Types](#message-type) that are used to request a [Catalog](#catalog) from a [Catalog Service](#catalog-service).

### Catalog Service

A [Participant Agent](#participant-agent) that makes a [Catalog](#catalog) available and accessible to [Participants](#participant).

### Connector (Data Service)

A [Participant Agent](#participant-agent) that performs [Contract Negotiation](#contract-negotiation) and [Transfer Process](#transfer-process) operations with other Connectors, by implementing [Dataspace Protocols](#dataspace-protocol). It produces [Agreements](#agreement) and manages [Dataset](#dataset) sharing.

### Consumer

A [Participant](#participant) that requests access to an offered [Dataset](#dataset).

### Contract Negotiation

A set of interactions between a [Provider](#provider) and [Consumer](#consumer) that establish an [Agreement](#agreement). It is an instantiation of the state machine of a [Contract Negotiation Protocol](#contract-negotiation-protocol). An outcome of a Contract Negotiation MAY be the production of an [Agreement](#agreement).

### Contract Negotiation Protocol

A set of allowable [Message Type](#message-type) sequences defined as a state machine.

## D

### Dataset

Data or a technical service that can be shared by a [Participant](#participant).

### dataspace

#### _data space_

[governance framework](#governance-framework) and supporting services to build [trustworthiness](#trustworthiness) and enable [data sharing](#data-sharing) through an agreed set of [Policies](#policy), semantic models, protocols and processes

[SOURCE: ISO/IEC DIS 20151]

### dataspace governance authority role

#### _DSGA role_

set of activities provided by one or more parties that establishes, governs, manages and enforces the technical policies and business rules of a [dataspace](#dataspace)

[SOURCE: ISO/IEC 20151 to be published]

### dataspace participant

#### _participant_

party that is acting in a [dataspace participant role](#dataspace-participant-role)

Note 1 to entry: By being accepted to be a participant in the dataspace, the party agrees to the governance arrangements and therefore the policies of the dataspace.
[SOURCE: ISO/IEC 20151 to be published]

Please also see [Participant](#participant) definition sourced from DSP.

### dataspace participant role

#### _participant role_

set of activities within a [dataspace](#dataspace) for the purpose of [data sharing](#data-sharing) or related activities
Note 1 to entry: Related activities can include auditing or observing roles that do not include data sharing or governance activities.
[SOURCE: ISO/IEC 20151 to be published]

### data policy

human and machine-readable set of rights and obligations regarding access and use of data
[SOURCE: ISO/IEC 20151 to be published]

### Dataspace Protocol

A set of Messages and Message sequences that enables the interaction between [Participant Agents](#participant-agent) in a [dataspace](#dataspace). This may require additional concepts, which are not in the scope of the specification itself.
A set of Messages and Message sequences that enables the interaction between [Participant Agents](#participant-agent) in a [Dataspace](#dataspace). This may require additional concepts, which are not in the scope of the specification itself.

### Data Transfer Protocol

A set of rules and conventions that dictate how data is transmitted over a network by defining the format, error handling, and flow control. Examples include HTTP, FTP, MQTT, and AMQP.

### data sharing

Access to the same data by more than one authorized entity
Note 1 to entry: Use of the data can be synchronous or asynchronous.
Note 2 to entry: Data can be shared, for example, (i) by allowing access to, or the execution of operations over, the
original dataset, or (ii) by giving a copy of the data to the interested entity.
Note 3 to entry: The way in which data is shared fundamentally influences the available controls and the statements
needed in a data sharing agreement.
[SOURCE: ISO/IEC 23751:2022[4], 3.7, modified - removed 'or processing of']

[SOURCE: ISO/IEC 20151 to be published]

### data sharing contract

formal and legally binding agreement between [dataspace participants](#dataspace-participant) containing policies, terms and
conditions for [data sharing](#data-sharing)
Note 1 to entry: Data sharing contracts usually contain information about access to data, including its metadata, and
data use.
Note 2 to entry: A data sharing contract is usually much more specific than a data sharing agreement which is often broader and often at an organizational level.
[SOURCE: ISO/IEC 20151 to be published]

Please also see [Agreement](#agreement) for a related definition sourced from DSP.

### data use

Handling or dealing with data for a specific purpose
[SOURCE: ISO/IEC 5207:2024[5](en), 3.30, modified – Note 1 to entry removed]
[SOURCE: ISO/IEC 20151 to be published]

## G

### governance

Human-based system comprising directing, overseeing and accountability [SOURCE: ISO/IEC 38500:2024[6], 3.3]
[SOURCE: ISO/IEC 20151 to be published]

### governance framework

Strategies, policies, decision-making structures and accountabilities through which the organization’s [governance](#governance) arrangements operate
[SOURCE: ISO/IEC TR 38502:2017[7], 3.1]
[SOURCE: ISO/IEC 20151 to be published]

## M

### Message Type

A definition of the structure of a Message.

## O

### Offer

A concrete [Policy](#policy) associated with a specific [Dataset](#dataset).

## P

### Participant

A member of one or more [Dataspaces](#dataspace) that provides and/or consumes [Datasets](#dataset). It registers [Participant Agents](#participant-agent) that perform tasks on its behalf.

Please also see [dataspace participant](#dataspace-participant) definition sourced from to be published ISO 20151

### Participant Agent

A technology system that performs operations and interactions in a [Dataspace](#dataspace) on behalf of a [Participant](#participant), such as publishing a [Catalog](#catalog) or engaging in a [Transfer Process](#transfer-process). It is a logical construct and does not necessarily correspond to a single runtime process. While most interactions take place between so-called Connectors, some interactions with other systems are required.

### Policy

A set of rules, duties, and obligations that define the terms of use for a [Dataset](#dataset).

### Profile

A restriction or subset of a specification that enforces every occurrence of an externally defined class to be conformant with the original definition.

### Provider

A [Participant](#participant) that offers a [Dataset](#dataset).

## T

### Transfer Process

A set of interactions between a [Provider](#provider) and [Consumer](#consumer) that give access to a [Dataset](#dataset) under the terms of an [Agreement](#agreement). It is an instantiation of the state machine of a [Transfer Process Protocol](#transfer-process-protocol).

### Transfer Process Protocol

A set of allowable [Message Type](#message-type) sequences defined as a state machine.

### trust

Decision by an entity to assume that a product, service or entity will behave as expected for a given circumstance

[SOURCE: ISO/IEC 20151 to be published]

### trustworthiness

set of verifiable evidence that can be used to form [trust](#trust)

[SOURCE: ISO/IEC 20151 to be published]
