# 2025 NCAA Men's Basketball Tournament Schedule and Predictions

This is the schedule of games for the 2025 NCAA Men's Basketball Tournament along with win probability predictions for each team provide by Chronulus AI.

For the first match up, the following prompt was used in Claude to setup the Chronulus Session and get the first prediction. Replace the items in `{{brackets}}` with your own values. 


``` 
The 2025 NCAA Men's basketball tournament starts tomorrow. I would like to make predictions for the first round of the tournament. 

Please a new Chronulus Session for this and setup a data model that you can plug in data for each match up separately. I want to reuse the same BinaryPredictor for each match up. In the task, be sure to specific that we want to predict the probability that team 1 wins the matchup.

As input data, I will give you images and injury reports (if one is available) for each match up in folder in my workspace. I have also include a PDF of the bracket and a text file with the current schedule in my workspace.

Pass these images and documents to Chronulus. Additionally, please include one field for "Additional context" and one for a list of additional images. In some matches, I will want to provide more details or additional images that are not available for other matches. These fields will be used for those.

In the fields that you create that contain information about a specific team, prefix the fields with 'team_1' and 'team_2' according how the team is listed in the match up I provide.

When you have the predictions, please save the results as html in `picks'.

Let's start..

Get the Chronulus predictions for this match up in {{'round1-south'}}: 

{{(8) Louisville vs. (9) Creighton, 12:15 p.m. | CBS}}
```


In subsequent conversations, the following prompt was used in Claude to reuse the session from the first match up. Again, replace the values in `{{brackets}}` with your own.

```
The 2025 NCAA Men's basketball tournament starts tomorrow. I would like to make predictions for the first round of the tournament. 

Please reuse the Chronulus session with session id = 'd2eb49bb-9dd4-5592-a050-8a04e926ae97' for this and setup a data model that you can plug in data for each match up separately. I want to reuse the same BinaryPredictor for each match up.

As input data, I will give you images and injury reports (if one is available) for each match up in folder in my workspace. I have also include a PDF of the bracket and a text file with the current schedule in my workspace.

Pass these images and documents to Chronulus. Additionally, please include one field for "Additional context" and one for a list of additional images. In some matches, I will want to provide more details or additional images that are not available for other matches. These fields will be used for those.

In the fields that you create that contain information about a specific team, prefix the fields with 'team_1' and 'team_2' according how the team is listed in the match up I provide. This needed because the session is setup to predict the probability that team 1 will win. So need to make sure this is correctly labeled.

When you have the predictions, please save the results as html in `picks'.

Let's start..

Please ask Chronulus to predict the probability that the first team listed in the following matchup will win. Use 5 experts.

Get the Chronulus predictions for this match up in {{'round1-midwest'}}: 

{{(4) Purdue vs. (13) High Point, 12:40 p.m. | truTV}}
```

## Tournament Schedule with Win Probability Predictions

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Round</th>
      <th>Region</th>
      <th>Team 1 (Seed)</th>
      <th>Team 2 (Seed)</th>
      <th>Team 1 Win %</th>
      <th>Team 2 Win %</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Mar 18</td>
      <td>First Four</td>
      <td>East</td>
      <td>Alabama State (16)</td>
      <td>Saint Francis (16)</td>
      <td>50.65%</td>
      <td>49.35%</td>
    </tr>
    <tr>
      <td>Mar 18</td>
      <td>First Four</td>
      <td>South</td>
      <td>San Diego State (11)</td>
      <td>North Carolina (11)</td>
      <td>45.43%</td>
      <td>54.57%</td>
    </tr>
    <tr>
      <td>Mar 19</td>
      <td>First Four</td>
      <td>East</td>
      <td>American University (16)</td>
      <td>Mount St. Mary's (16)</td>
      <td>51.41%</td>
      <td>48.59%</td>
    </tr>
    <tr>
      <td>Mar 19</td>
      <td>First Four</td>
      <td>Midwest</td>
      <td>Texas (11)</td>
      <td>Xavier (11)</td>
      <td>49.87%</td>
      <td>50.13%</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>East</td>
      <td>Louisville (8)</td>
      <td>Creighton (9)</td>
      <td>49.59%</td>
      <td>50.41%</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>Midwest</td>
      <td>Purdue (4)</td>
      <td>High Point (13)</td>
      <td>85.76%</td>
      <td>14.23%</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>West</td>
      <td>Wisconsin (3)</td>
      <td>Montana (14)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>South</td>
      <td>Houston (1)</td>
      <td>SIU Edwardsville (16)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>East</td>
      <td>Auburn (1)</td>
      <td>TBD (16)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>West</td>
      <td>Clemson (5)</td>
      <td>McNeese (12)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>South</td>
      <td>BYU (6)</td>
      <td>VCU (11)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>Midwest</td>
      <td>Gonzaga (8)</td>
      <td>Georgia (9)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>South</td>
      <td>Tennessee (2)</td>
      <td>Wofford (15)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>East</td>
      <td>Kansas (7)</td>
      <td>Arkansas (10)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>West</td>
      <td>Texas A&M (4)</td>
      <td>Yale (13)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>Midwest</td>
      <td>Missouri (6)</td>
      <td>Drake (11)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>South</td>
      <td>UCLA (7)</td>
      <td>Utah State (10)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>East</td>
      <td>St. John's (2)</td>
      <td>Omaha (15)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>Midwest</td>
      <td>Michigan (5)</td>
      <td>UC San Diego (12)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 20</td>
      <td>First Round</td>
      <td>West</td>
      <td>Texas Tech (3)</td>
      <td>UNC Wilmington (14)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>West</td>
      <td>Mississippi State (8)</td>
      <td>Baylor (9)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>South</td>
      <td>Alabama (2)</td>
      <td>Robert Morris (15)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>Midwest</td>
      <td>Iowa State (3)</td>
      <td>Lipscomb (14)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>East</td>
      <td>Memphis (5)</td>
      <td>Colorado State (12)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>West</td>
      <td>Duke (1)</td>
      <td>TBD (16)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>Midwest</td>
      <td>Saint Mary's (7)</td>
      <td>Vanderbilt (10)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>South</td>
      <td>Ole Miss (6)</td>
      <td>TBD (11)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>East</td>
      <td>Maryland (4)</td>
      <td>Grand Canyon (13)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>Midwest</td>
      <td>Florida (1)</td>
      <td>Norfolk State (16)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>South</td>
      <td>Kentucky (3)</td>
      <td>Troy (14)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>West</td>
      <td>Marquette (7)</td>
      <td>New Mexico (10)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>East</td>
      <td>Arizona (4)</td>
      <td>Akron (13)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>West</td>
      <td>UConn (8)</td>
      <td>Oklahoma (9)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>Midwest</td>
      <td>Illinois (6)</td>
      <td>TBD (11)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>South</td>
      <td>Michigan State (2)</td>
      <td>Bryant (15)</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mar 21</td>
      <td>First Round</td>
      <td>East</td>
      <td>Oregon (5)</td>
      <td>Liberty (12)</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

## Venue Information

| Round | City | Venue | Dates | Host |
|-------|------|-------|-------|------|
| First Four | Dayton, Ohio | UD Arena | March 18 - 19 | University of Dayton |
| First/Second | Lexington, KY | Rupp Arena | March 20 - 22 | University of Kentucky |
| First/Second | Providence, RI | Amica Mutual Pavilion | March 20 - 22 | Providence College |
| First/Second | Seattle, WA | Climate Pledge Arena | March 21 - 23 | University of Washington |
| First/Second | Wichita, KS | Intrust Bank Arena | March 20 - 22 | Wichita State University |
| First/Second | Cleveland, OH | Rocket Arena | March 21 - 23 | Mid-American Conference |
| First/Second | Denver, CO | Ball Arena | March 20 - 22 | Mountain West Conference |
| First/Second | Milwaukee, WI | Fiserv Forum | March 21 - 23 | Marquette University |
| First/Second | Raleigh, NC | Lenovo Center | March 21 - 23 | NC State University |
| East Regional | Newark, NJ | Prudential Center | March 27 - 29 | Seton Hall University |
| West Regional | San Francisco, CA | Chase Center | March 27 - 29 | Pac-12 Conference |
| South Regional | Atlanta, GA | State Farm Arena | March 28 - 30 | Georgia Institute of Technology |
| Midwest Regional | Indianapolis, IN | Lucas Oil Stadium | March 28 - 30 | IU Indianapolis/Horizon League |
| Final Four | San Antonio, TX | Alamodome | April 5 & 7 | | 

---
*Data updated as of March 17, 2025. Win probability predictions based on Chronulus AI forecasting models.*