[U4Academy](../../README.md) > [Release Notes Student App](README.md) > API updates

## <span style="color:#70ad47">API updates</span>  
___
This section contains important information regarding API updates.

### <span style="color:#70ad47">Student management</span><br>

<details>
<summary><span style="color:#88AEC9"><b>Removal of fields in API</b></span></summary>
<br>

&nbsp;&nbsp;<font size="2">_**Benefit**: Configuration is aligned with allowed changes in Web._</font>

&nbsp;&nbsp;Now, the Student App API does not include the following fields in the response and request body to **create** and **update** students, and in the response to **get** and **get all** students:
- _University_
- _Address_

> Note: The mode schema has been changed, therefore these fields must be removed from the existing API calls.

</details>

<br>
<details>
<summary><span style="color:#88AEC9"><b>Addition of fields in API</b></span></summary>
<br>

&nbsp;&nbsp;<font size="2">_**Benefit**: Configuration is aligned with allowed changes in Web._</font>

&nbsp;&nbsp;Now, the Student App API  includes the following fields in the response and request to  **create** and **update** students, and in the response to **get** and **get all** students:
+ _City_
+ _Languages_
+ _Work location_
+ _Programming Languages_

>Note: The mode schema has been changed, therefore these fields must be added to the existing API calls.
</details>
