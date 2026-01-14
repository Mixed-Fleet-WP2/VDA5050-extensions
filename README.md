# Supplementary material for paper "*Beyond AGVs: Extending VDA5050 from AGVs to UAVs toward system level interoperability*"

This repository provides the proposed JSON schemas and a summary table detailing the extensions to the [VDA5050 standard](https://www.vda.de/en/topics/automotive-industry/vda-5050) v.2.1.0 introduced in the paper _Beyond AGVs: Extending VDA5050 from AGVs to UAVs Toward System-Level Interoperability_. The paper is available from the following link: [Paper link] These materials illustrate how the standard was adapted to support UAVs and enable system-level interoperability. The contents of the repository are as follows:

- __proposed_schema_changes.csv__ contains a summary of all the schema changes made as part of the study. The headers are as follows:
    - __Field__: The name of the schema field subject to change
    - __Description__: Description of the field
    - __Change__: Specifies the type of change (new field, removed field, type change, replacement or semantic modification)
    - __Basis schema__: Name of the original VDA5050 schema which served as the basis for changes. These may be found in the _original_ directory in this repository or from the [VDA5050 repository](https://github.com/VDA5050/VDA5050/tree/release/2.1.0)
    - __New schema__: Name of the new schema that is the result of changes to the __Basis schema__. If the field values are the same, the changes are proposed to be made to the original schema directly.
    - __Related feature__: Describes a feature that the field change relates to. See the related paper for details.
    - __Rational__: For removed fields, contains a brief explanation for why the field was removed as part of the study's results

- __complex_return_types__/: JSON chemas related to section 5B.2 _Supporting three-dimensional navigation_
- __3d_nav__/: JSON chemas related to section 5B.1 _Extending action result representations_
- __elevator__/: JSON chemas related to section 5B.3 _Elevator communication_
- __original__/: Contains copies of the original VDA5050 schemas (v.2.1.0) copied from the official VDA5050 repository. This aims to make comparison of the changes easier
