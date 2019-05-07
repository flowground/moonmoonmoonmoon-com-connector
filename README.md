# ![LOGO](logo.png) Moon by Ai Weiwei & Olafur Eliasson **flow**ground Connector

## Description

A generated **flow**ground connector for the Moon by Ai Weiwei & Olafur Eliasson API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/moonmoonmoonmoon.com/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:04+03:00

## API Description

Turn nothing into something – make a drawing, make a mark.

## Authorization

This API does not require authorization.

## Actions

### Fetches popular hashtags or marks tagged with specified hashtag

> Search for specified tag (no pound sign necessary). If <b>tag</b> is empty, the 50 most popular hashtags will be returned.

*Tags:* `marks`

#### Input Parameters
* `tag` - _optional_ - Hashtag to search for

### Fetches marks

> The main method for querying the marks database. You may use the following options:<br/>
>         <ol style='list-style-type: lower-roman;'><br/>
>         <li>No parameters to retrieve all marks in descending chronological order (use <b>before</b> for pagination)</li><br/>
>         <li><b>popular</b> (and optionally <b>last_popular_id</b>) to retrieve all popular marks</li><br/>
>         <li><b>featured</b> to retrieve all featured marks</li><br/>
>         <li><b>x & y</b> to retrieve mark at specific coordinate</li><br/>
>         <li><b>user</b> to retrieve all marks created by the specified user</li><br/>
>         <li><b>collection</b> to retrieve all marks collected by the specified user</li><br/>
>         </ol>

*Tags:* `marks`

#### Input Parameters
* `before` - _optional_ - Before ID (pagination purposes)
* `popular` - _optional_ - Popular marks
* `last_popular_id` - _optional_ - Last popular ID (for pagination purposes)
* `featured` - _optional_ - Featured marks
* `x` - _optional_ - X coordinate
* `y` - _optional_ - Y coordinate
* `user` - _optional_ - Created by user ID
* `collection` - _optional_ - Collection ID

## License

**flow**ground :- Telekom iPaaS / moonmoonmoonmoon-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
