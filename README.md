
## Maths branch

<table>
<tr><th>Project</th><th>Team</th><th>Time</th><th>XP</th><th>Description</th></tr>
<tr><td>ready_set_boole <td>Solo<td>10days<td>7000<td>Discover the way computers work mathematically.</tr>
<tr><td>matrix <td>Solo<td>10days<td>7000<td>Vectors and matrices, basically.</tr>
<tr><td>ft_kalman <td>Group 1-2<td>210h<td>16800<td>For this project, you will need to create a kalman filter to retrace a trajectory with incomplete and flawed information.</tr>
<tr><td>computorv1 <td>Solo<td>49h<td>4200<td>This project is the first in a series that aims to make you rekindle with maths. They will be quite useful - not to say essential - for numerous projects to come.</tr>
<tr><td>computorv2 <td>Solo<td>147h<td>9450<td>This project is the first of a serie to renew your relationship to mathematics, it will be very useful, essential even, for many more projects.</tr>
</table>

```mermaid
pie  title XP for maths projects
	"ready_set_boole"  : 7000
	"matrix"  : 7000
	"ft_kalman"  : 16800
	"computorv1"  : 4200
	"computorv2"  : 9450
```

```mermaid
pie  title required time for maths projects
	"ready_set_boole"  : 240
	"matrix"  : 240
	"ft_kalman"  : 210
	"computorv1"  : 49
	"computorv2"  : 147
```


### maths branch
```mermaid
flowchart LR
	0(maths) --240h, 7000XP--> A((matrix))
	B((ft_kalman)):::group
	A --210h, 16800XP --> B
	0 --240h, 7000XP--> E((ready_set_boole))
	0 --49h, 4200XP--> C((computorv1)) -- 147h, 9450XP --> D((computorv1))
    classDef group fill:#f96
```
