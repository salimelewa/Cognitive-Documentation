<!-- 
NavPath: Academic Knowledge API/Knowledge Exploration/Entity Attributes
LinkLabel: Author Entity
Url: Academic-Knowledge-API/documentation/KnowledgeExploration/EntityAttributes/AuthorEntity
Weight: 680
-->

# Author Entity
<sub>
*Below attributes are specific to author entity. (Ty = '1')
</sub>

Name	|Description							|Type       | Operations
------- | ------------------------------------- | --------- | ----------------------------
Id		|Entity ID								|Int64		|Equals
AuN		|Author normalized name					|String		|Equals
DAuN	|Author display name					|String		|none
CC		|Author total citation count			|Int32		|none  
ECC		|Author total estimated citation count	|Int32		|none
E		|Extended metadata (see table below) 	|String 	|none  

## Extended Metadata Attributes ##

Name    | Description               
--------|---------------------------	
LKA.Afn		| Last known affiliation's display name associated with the author  
LKA.AfId		| Last known affiliation's entity ID associated with the author