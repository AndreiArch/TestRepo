***Before you begin, This is our First picture*** 

![](./Assets/montaing.jpg)

***Here you can find the design brand*** 

![](./Assets/Design.jpg)

1. Sign in to the **Locusview web app** and go to **Yada**.
1. You should do so and so.
1. You should verify so and so.

:::(Error) (**NOTE**)
Discalimer 123 testing 123.
:::

# Heading 1

## Heading 2

To create a new integration:
- [Setting Up Integration Properties](#heading3).
- [Setting Up Integration Flows](#heading4).
- [Setting Up Integration Entity Mappings](#heading5).
- [Setting Up Integration Field Mappings](#heading22).

### Heading 3

To set up the integration properties:

1. Sign in to the **web app** and go to **Section**.
2. Select **New** (plus icon) to create a new integration.
3. On the **Integration**, set as follows:

![image](https://link/Documentation/IM_New_Integration_Properties.JPG)

*Figure: new integration creation in the Integration Manager*

|Property | Values | Description|
|---------|------------|------------|
|Integration Name| Text string | The property is mandatory and must be filled.The options are: <br> 1. option 1. <br> 2. option 2.<br> 3. option 3.|
|Description|Text string | The property can explain the integration and any further details deemed important. |
|Connection| All predefined [Connections](#managing-connections)| The property determines the attached connection. The property is mandatory and must be filled.|

4. Save the changes made by:
	1. option 1.
	2. option 2.
6. Select **Close** to return to the main **Integrations** screen.

### Headong 33

To set up integration flows:

1. Go to **Main** (Integration Manager module) > **Blah** section.
1. On the **Integration Flow Editor** set its **Properties** by filling in the data as follows:

![image](https://link/IM_New_Integration_Flow_Properties.JPG)

*Figure: new integration flow creation in the Integration Manager*

|Property | Values | Description|
|---------|------------|------------|
|Description|Text string | The property can explain the integration flow and any further details deemed important. |
|Flow Direction| Outbound| The property determines the direction of the data flow within the integration. Outbound sets the data to go from Locusview out to the connected Platform. The property is mandatory.<br> <br> **NOTE**: yadh yadh yadh blah blah.|
|Change Status to| Exported| After executing it successfully, The property determines the desired status of approved work order changes. The options are: <br>- Exported: blah blah.<br>- New: blah blah.|

#### Heading 44

To set up the integration entity mappings:

1. Sign in to the **Locusview web app** and go to **Integrations** (Integration Manager module) > **Integrations** section.
2. Go to desired integration followed by the **Integration Flows** tab.
3. Select the desired integration flow.
4. Select the **New** (plus icon) to create a new entity mapping.
5. In the **Entity Mapping Editor**, set it  as follows:

![image](https://link/IM_New_Entity_Map_Create.JPG)

*Figure: new entity mapping creation in the Integration Manager*

|Property | Values | Description|
|---------|------------|------------|
|Description|Text string | The property can explain the integration and any further details deemed important. |
|Source Entity Type| - Asset Type <br>- Form Type <br>- Work Unit Type <br>- Work Order Type | The property determines the Locusview entity type to use. The property is mandatory.|
|Source Asset/For/Work Unit/ Work Order Type| All predefined Entities based on the selected Entity Type | The property name and list of optional values depend on the Source Entity Type property selection. The property is mandatory.|
|Target Endpoint| All predefined [Connection](/link to another page)| The property determines the connected target destination endpoint. The property is mandatory.|
|Target Entity| Text String| The property determines the connected target designated entity or object to add to the select Target Endpoint path. The property is mandatory.|
|Set Mapping Condition| see [entity mapping condition](#setting-up-entity-mapping-conditions) setup| The property determines the Entity Mapping conditionality and criteria.|

6. Save the changes made.
7. Select **Close** to return to the main **Integration Flows** screen.


## Heading 22

### Editing Integration Properties

To edit the integration properties:

1. Sign in to the **Locusview** and go to **Blah**.

|Property | Values | Description|
|---------|------------|------------|
|Integration Name| Text string | The property determines the name of the integration. The property is mandatory and must be filled.|
|Description|Text string | The property can explain the integration and any further details deemed important. |
|Connection| All predefined [Connections](/link to another page#section-within-the-page)| The property determines the attached connection. The property is mandatory and must be filled.The options are:<br>1. **Option 1**:blah blah blah blah blah blah.<br>2. **Option 2**:blah blah blah blah blah blah.|

2. Save the changes made.
3. Select **Close** to return to the main **Integrations** screen.

##### Heading 5

To edit integration flows:

1. Go to **Integrations** (Integration Manager module) > **Integrations** section.
1. Select the desired integration and go to its **Integration Flows** tab.
1. Select the desired integration flow.
1. On the **Integration Flow Editor** set its **Properties** by filling in the data as follows:

|Property | Values | Description|
|---------|------------|------------|
|Integration Name| Text string | The property determines the name the blah blah blah blah blah.|
|Description|Text string | The property can explain the integration flow and any further details deemed important. |
|Change Status to| - 1 <br>- 2| The property determines the desired status of approved work order changes. The options are <br>- 1: every approved work order will have an exported status post a successful run. The property is mandatory.<br>- 2: every approved work order will have an exported status post a successful run. The property is mandatory.|

5. Save the changes made.
6. Select **Close** to return to the main **Integration Flows** screen.

:::(Info) (**NOTE**)
The use of Data transformation is not mandatory. The option is to set a field mapping with or without Data Transformation.
:::

##### Heading 55

1. **Option 111**: option bla bla bla
2. **Option 222**: option bla bla bla
3. **Option 333**: option bla bla bla
	- **option 333 - 1**: yada yada yada.
	- **option 333 - 2**: yada yada yada yada..
4. **Option 444**: option bla bla bla

testing testing 123




