<?xml version="1.0" encoding="UTF-8"?>
<table xmlns="http://query.yahooapis.com/v1/schema/table.xsd">
    <meta>
        <sampleQuery></sampleQuery>
    </meta>
    <bindings>
        <select itemPath="json.loans" produces="JSON">
            <urls>
                <url>http://api.kivaws.org/v1/loans/{ids}.json</url>
            </urls>
            <inputs>
                <key id='ids' type='xs:string' paramType='path' required="true" />
                <key id='app_id' type='xs:string' paramType='query' required="false" />
            </inputs>
        </select> 
    </bindings>
</table>
