
ISO-XML Geodatensatz
====================

<?xml version="1.0" encoding="UTF-8"?>

<gmd:MD_Metadata xmlns:
gmd="http://www.isotc211.org/2005/gmd"


XML Namespaces (Namensräume)
''''''''''''''''''''''''''''

xmlns:gco="http://www.isotc211.org/2005/gco" 
xmlns:gml="http://www.opengis.net/gml/3.2" 
xmlns:gmx="http://www.isotc211.org/2005/gmx" 
xmlns:gts="http://www.isotc211.org/2005/gts" 
xmlns:igctx="https://www.ingrid-oss.eu/schemas/igctx" 
xmlns:srv="http://www.isotc211.org/2005/srv" 
xmlns:xlink="http://www.w3.org/1999/xlink" 
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
xsi:schemaLocation="http://www.isotc211.org/2005/gmd http://repository.gdi-de.org/schemas/geonetwork/2020-12-11/csw/2.0.2/profiles/apiso/1.0.1/apiso.xsd">
  
Objekt-ID
'''''''''

  <gmd:fileIdentifier>
    <gco:CharacterString>7AFF5BF1-1CA3-4168-9E66-016A00B1AD50</gco:CharacterString>
  </gmd:fileIdentifier>


Sprache des Metadatensatzes
'''''''''''''''''''''''''''

  <gmd:language>
    <gmd:LanguageCode codeList="http://www.loc.gov/standards/iso639-2/" codeListValue="ger"/>
  </gmd:language>


Zeichensatz des Datensatzes
'''''''''''''''''''''''''''

  <gmd:characterSet>
    <gmd:MD_CharacterSetCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_CharacterSetCode" codeListValue="utf8"/>
  </gmd:characterSet>


Datensatz/Datenserie
''''''''''''''''''''

  <gmd:hierarchyLevel>
    <gmd:MD_ScopeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_ScopeCode" codeListValue="dataset">dataset</gmd:MD_ScopeCode>
  </gmd:hierarchyLevel>


Verantwortlicher
''''''''''''''''
  <gmd:contact>
    <gmd:CI_ResponsibleParty uuid="806C2820-C94D-4D5D-8800-934B2C91D8C5">
      <gmd:organisationName>
        <gco:CharacterString>Landesamt für Vermessung und Geoinformation (LVermGeo) Sachsen-Anhalt / Landesamt für Vermessung und Geoinformation (LVermGeo) Sachsen-Anhalt</gco:CharacterString>
      </gmd:organisationName>
      <gmd:contactInfo>
        <gmd:CI_Contact>
          <gmd:address>
            <gmd:CI_Address>
              <gmd:electronicMailAddress>
                <gco:CharacterString>service.lvermgeo@sachsen-anhalt.de</gco:CharacterString>
              </gmd:electronicMailAddress>
            </gmd:CI_Address>
          </gmd:address>
        </gmd:CI_Contact>
      </gmd:contactInfo>
      <gmd:role>
        <gmd:CI_RoleCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_RoleCode" codeListValue="pointOfContact"/>
      </gmd:role>
    </gmd:CI_ResponsibleParty>
  </gmd:contact>


Zeitstempel
'''''''''''
  <gmd:dateStamp>
    <gco:Date>2022-10-28</gco:Date>
  </gmd:dateStamp>


ISO-Norm
''''''''
  <gmd:metadataStandardName>
    <gco:CharacterString>ISO19115</gco:CharacterString>
  </gmd:metadataStandardName>

  <gmd:metadataStandardVersion>
    <gco:CharacterString>2003/Cor.1:2006</gco:CharacterString>
  </gmd:metadataStandardVersion>


Raumbezug
'''''''''
  <gmd:referenceSystemInfo>
    <gmd:MD_ReferenceSystem>
      <gmd:referenceSystemIdentifier>
        <gmd:RS_Identifier>
          <gmd:code>
            <gmx:Anchor xlink:href="http://www.opengis.net/def/crs/EPSG/0/4258">EPSG 4258: ETRS89 / geographisch</gmx:Anchor>
          </gmd:code>
        </gmd:RS_Identifier>
      </gmd:referenceSystemIdentifier>
    </gmd:MD_ReferenceSystem>
  </gmd:referenceSystemInfo>


  <gmd:identificationInfo>

    <gmd:MD_DataIdentification uuid="https://registry.gdi-de.org/id/de.st/lvermgeo.gn.alkis">

      <gmd:citation>
        <gmd:CI_Citation>


Titel
'''''
          <gmd:title>
            <gco:CharacterString>INSPIRE ST Geografische Bezeichnungen ALKIS</gco:CharacterString>
          </gmd:title>


Kurzbezeichnung
'''''''''''''''
          <gmd:alternateTitle>
            <gco:CharacterString>ALKIS</gco:CharacterString>
          </gmd:alternateTitle>


Datum
'''''
          <gmd:date>
            <gmd:CI_Date>
              <gmd:date>
                <gco:DateTime>2017-11-23T00:00:00.000+01:00</gco:DateTime>
              </gmd:date>
              <gmd:dateType>
                <gmd:CI_DateTypeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_DateTypeCode" codeListValue="creation"/>
              </gmd:dateType>
            </gmd:CI_Date>
          </gmd:date>


Identifikator der DatenQuelle
'''''''''''''''''''''''''''''
          <gmd:identifier>
            <gmd:MD_Identifier>
              <gmd:code>
                <gco:CharacterString>https://registry.gdi-de.org/id/de.st/lvermgeo.gn.alkis</gco:CharacterString>
              </gmd:code>
            </gmd:MD_Identifier>
          </gmd:identifier>

        </gmd:CI_Citation>
      </gmd:citation>


Beschreibung
''''''''''''
      <gmd:abstract>
        <gco:CharacterString>Kostenpflichtiger INSPIRE-Datensatz zum Annex1-Thema Geografische Bezeichnungen für das Bundesland Sachsen-Anhalt. Der Datensatz wurde aus den Daten des ALKIS abgeleitet und INSPIRE-konform transformiert.</gco:CharacterString>
      </gmd:abstract>


UUID
''''
      <gmd:pointOfContact>
        <gmd:CI_ResponsibleParty uuid="62B5B897-DC4B-11D2-9A86-080000507261">

         
Organisationsname
'''''''''''''''''
          <gmd:organisationName>
            <gco:CharacterString>Landesamt für Vermessung und Geoinformation (LVermGeo) Sachsen-Anhalt</gco:CharacterString>
          </gmd:organisationName>


Beschreibung
''''''''''''
          <gmd:positionName>
            <gco:CharacterString>Das Landesamt für Vermessung und Geoinformation Sachsen-Anhalt (LVermGeo) gliedert sich in Funktionsmanagement und Produktionsmanagement. Das Produktionsmanagement ist in einem nicht selbständigen Geoleistungsbereich mit regionaler Aufteilung in vier Standorte strukturiert. Das Funktionsmanagement ist am Behördensitz in Magdeburg konzentriert. Das Call-Center ist die zentrale Anlaufstelle für alle Auskünfte und Beratungen.  
Zu den Aufgaben des LVermGeo gehören:  
- die Landesvermessung mit den Bereichen Grundlagenvermessung,Topographische   Landesaufnahme und Topgraphische Landeskartenwerke,
- die Führung des Liegenschaftskatasters mit den   Nachweisen Liegenschaftskarte und Liegenschaftsbuch,
- die Grundstückswertermittlung mit der  Kaufpreissammlung, den Bodenrichtwerten und den  Grundstücksmarktberichten,
- die Bereitstellung des Geobasisinformationssystems  mit den Komponenten Liegenschaften und  Geotopographie und
- der Aufbau einer Geodateninfrastruktur für Sachsen- Anhalt.</gco:CharacterString>
          </gmd:positionName>

          <gmd:contactInfo>
            <gmd:CI_Contact>
              <gmd:phone>
                <gmd:CI_Telephone>


Telefonnummer
'''''''''''''
                  <gmd:voice>
                    <gco:CharacterString>0391 567-8585</gco:CharacterString>
                  </gmd:voice>


Faxnummer
'''''''''   
                  <gmd:facsimile>
                    <gco:CharacterString>0391 567-8686</gco:CharacterString>
                  </gmd:facsimile>

                </gmd:CI_Telephone>
              </gmd:phone>


Adresse
^^^^^^^
              <gmd:address>
                <gmd:CI_Address>
                  <gmd:deliveryPoint>
                    <gco:CharacterString>Otto-von-Guericke-Straße 15</gco:CharacterString>
                  </gmd:deliveryPoint>
                  <gmd:city>
                    <gco:CharacterString>Magdeburg</gco:CharacterString>
                  </gmd:city>
                  <gmd:administrativeArea>
                    <gco:CharacterString>Sachsen-Anhalt</gco:CharacterString>
                  </gmd:administrativeArea>
                  <gmd:postalCode>
                    <gco:CharacterString>D-39104</gco:CharacterString>
                  </gmd:postalCode>
                  <gmd:country>
                    <gco:CharacterString>DEU</gco:CharacterString>
                  </gmd:country>
                  <gmd:electronicMailAddress>
                    <gco:CharacterString>service.lvermgeo@sachsen-anhalt.de</gco:CharacterString>
                  </gmd:electronicMailAddress>
                </gmd:CI_Address>
              </gmd:address>


URL
'''
              <gmd:onlineResource>
                <gmd:CI_OnlineResource>
                  <gmd:linkage>
                    <gmd:URL>https://www.lvermgeo.sachsen-anhalt.de</gmd:URL>
                  </gmd:linkage>
                </gmd:CI_OnlineResource>
              </gmd:onlineResource>
            </gmd:CI_Contact>
          </gmd:contactInfo>


Codelist - Kontakt
''''''''''''''''''
          <gmd:role>
            <gmd:CI_RoleCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_RoleCode" codeListValue="pointOfContact"/>
          </gmd:role>

        </gmd:CI_ResponsibleParty>
      </gmd:pointOfContact>


UUID
''''
      <gmd:pointOfContact>
        <gmd:CI_ResponsibleParty uuid="62B5B897-DC4B-11D2-9A86-080000507261">


Organisationsname
'''''''''''''''''
          <gmd:organisationName>
            <gco:CharacterString>Landesamt für Vermessung und Geoinformation (LVermGeo) Sachsen-Anhalt</gco:CharacterString>
          </gmd:organisationName>


Beschreibung
''''''''''''
          <gmd:positionName>
            <gco:CharacterString>Das Landesamt für Vermessung und Geoinformation Sachsen-Anhalt (LVermGeo) gliedert sich in Funktionsmanagement und Produktionsmanagement. Das Produktionsmanagement ist in einem nicht selbständigen Geoleistungsbereich mit regionaler Aufteilung in vier Standorte strukturiert. Das Funktionsmanagement ist am Behördensitz in Magdeburg konzentriert. Das Call-Center ist die zentrale Anlaufstelle für alle Auskünfte und Beratungen.  
Zu den Aufgaben des LVermGeo gehören:  
- die Landesvermessung mit den Bereichen Grundlagenvermessung,Topographische   Landesaufnahme und Topgraphische Landeskartenwerke,
- die Führung des Liegenschaftskatasters mit den   Nachweisen Liegenschaftskarte und Liegenschaftsbuch,
- die Grundstückswertermittlung mit der  Kaufpreissammlung, den Bodenrichtwerten und den  Grundstücksmarktberichten,
- die Bereitstellung des Geobasisinformationssystems  mit den Komponenten Liegenschaften und  Geotopographie und
- der Aufbau einer Geodateninfrastruktur für Sachsen- Anhalt.</gco:CharacterString>
          </gmd:positionName>


          <gmd:contactInfo>
            <gmd:CI_Contact>
              <gmd:phone>
                <gmd:CI_Telephone>


Telefonnummer
'''''''''''''                
                  <gmd:voice>
                    <gco:CharacterString>0391 567-8585</gco:CharacterString>
                  </gmd:voice>


Faxnummer
'''''''''
                  <gmd:facsimile>
                    <gco:CharacterString>0391 567-8686</gco:CharacterString>
                  </gmd:facsimile>


                </gmd:CI_Telephone>
              </gmd:phone>


Adresse
^^^^^^^
              <gmd:address>
                <gmd:CI_Address>
                  <gmd:deliveryPoint>
                    <gco:CharacterString>Otto-von-Guericke-Straße 15</gco:CharacterString>
                  </gmd:deliveryPoint>
                  <gmd:city>
                    <gco:CharacterString>Magdeburg</gco:CharacterString>
                  </gmd:city>
                  <gmd:administrativeArea>
                    <gco:CharacterString>Sachsen-Anhalt</gco:CharacterString>
                  </gmd:administrativeArea>
                  <gmd:postalCode>
                    <gco:CharacterString>D-39104</gco:CharacterString>
                  </gmd:postalCode>
                  <gmd:country>
                    <gco:CharacterString>DEU</gco:CharacterString>
                  </gmd:country>
                  <gmd:electronicMailAddress>
                    <gco:CharacterString>service.lvermgeo@sachsen-anhalt.de</gco:CharacterString>
                  </gmd:electronicMailAddress>
                </gmd:CI_Address>
              </gmd:address>

URL
'''
              <gmd:onlineResource>
                <gmd:CI_OnlineResource>
                  <gmd:linkage>
                    <gmd:URL>https://www.lvermgeo.sachsen-anhalt.de</gmd:URL>
                  </gmd:linkage>
                </gmd:CI_OnlineResource>              
              </gmd:onlineResource>

            </gmd:CI_Contact>
          </gmd:contactInfo>

Codelist - Urheber
''''''''''''''''''
          <gmd:role>
            <gmd:CI_RoleCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_RoleCode" codeListValue="originator"/>
          </gmd:role>

        </gmd:CI_ResponsibleParty>
      </gmd:pointOfContact>


Zeitbezug
'''''''''
      <gmd:resourceMaintenance>
        <gmd:MD_MaintenanceInformation>
          <gmd:maintenanceAndUpdateFrequency gco:nilReason="missing"/>
          <gmd:updateScope>
            <gmd:MD_ScopeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_ScopeCode" codeListValue="dataset"/>
          </gmd:updateScope>
          <gmd:maintenanceNote>
            <gco:CharacterString>Der Datensatz wird vierteljährlich gegenüber dem Primärdatenbestand aktualisiert.</gco:CharacterString>
          </gmd:maintenanceNote>
        </gmd:MD_MaintenanceInformation>
      </gmd:resourceMaintenance>


Vorschaugrafik
^^^^^^^^^^^^^^
      <gmd:graphicOverview>
        <gmd:MD_BrowseGraphic>


Dateiname
'''''''''        
          <gmd:fileName>
            <gco:CharacterString>https://test.metaver.de/documents/ingrid-group_ige-iplug-st/7AFF5BF1-1CA3-4168-9E66-016A00B1AD50/Vorschaugrafik%20INSPIRE-Datensatz%20Geografische%20Bezeichnungen%20aus%20ALKIS%20mit%20Hintergrundkarte.png</gco:CharacterString>
          </gmd:fileName>

Bezeichnung
'''''''''''
          <gmd:fileDescription>
            <gco:CharacterString>Vorschaugrafik INSPIRE-Datensatz Geografische Bezeichnungen aus ALKIS mit Hintergrundkarte</gco:CharacterString>
          </gmd:fileDescription>
        </gmd:MD_BrowseGraphic>
      </gmd:graphicOverview>


Vorschaugrafik
^^^^^^^^^^^^^^
      <gmd:graphicOverview>
        <gmd:MD_BrowseGraphic>


Dateiname
''''''''' 
          <gmd:fileName>
            <gco:CharacterString>https://test.metaver.de/documents/ingrid-group_ige-iplug-st/7AFF5BF1-1CA3-4168-9E66-016A00B1AD50/Vorschaugrafik%20INSPIRE-Datensatz%20Geografische%20Bezeichnungen%20aus%20ALKIS%20ohne%20Hintergrundkarte.png</gco:CharacterString>
          </gmd:fileName>


Bezeichnung
'''''''''''
          <gmd:fileDescription>
            <gco:CharacterString>Vorschaugrafik INSPIRE-Datensatz Geografische Bezeichnungen aus ALKIS ohne Hintergrundkarte</gco:CharacterString>
          </gmd:fileDescription>
        </gmd:MD_BrowseGraphic>
      </gmd:graphicOverview>


      <gmd:descriptiveKeywords>
        <gmd:MD_Keywords>

          <gmd:keyword>
            <gco:CharacterString>Geografische Bezeichnungen</gco:CharacterString>
          </gmd:keyword>

          <gmd:type>
            <gmd:MD_KeywordTypeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_KeywordTypeCode" codeListValue="theme"/>
          </gmd:type>

          <gmd:thesaurusName>
            <gmd:CI_Citation>


Thesaurusname - Gemet
'''''''''''''''''''''            
              <gmd:title>
                <gco:CharacterString>GEMET - INSPIRE themes, version 1.0</gco:CharacterString>
              </gmd:title>


              <gmd:date>
                <gmd:CI_Date>


Publikationsdatum
'''''''''''''''''
                  <gmd:date>
                    <gco:Date>2008-06-01</gco:Date>
                  </gmd:date>

                  <gmd:dateType>
                    <gmd:CI_DateTypeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_DateTypeCode" codeListValue="publication">publication</gmd:CI_DateTypeCode>
                  </gmd:dateType>


                </gmd:CI_Date>
              </gmd:date>
            </gmd:CI_Citation>
          </gmd:thesaurusName>
        </gmd:MD_Keywords>
      </gmd:descriptiveKeywords>


      <gmd:descriptiveKeywords>

Verschlagwortung
^^^^^^^^^^^^^^^^
        <gmd:MD_Keywords>

          <gmd:keyword>
            <gco:CharacterString>Geobasisdaten</gco:CharacterString>
          </gmd:keyword>


          <gmd:keyword>
            <gco:CharacterString>Sachsen-Anhalt</gco:CharacterString>
          </gmd:keyword>


          <gmd:type>
            <gmd:MD_KeywordTypeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_KeywordTypeCode" codeListValue="theme"/>
          </gmd:type>

          <gmd:thesaurusName>
            <gmd:CI_Citation>


Thesaurusname-UMTHES
''''''''''''''''''''
              <gmd:title>
                <gco:CharacterString>UMTHES Thesaurus</gco:CharacterString>
              </gmd:title>

              <gmd:date>
                <gmd:CI_Date>
                  <gmd:date>
                    <gco:Date>2009-01-15</gco:Date>
                  </gmd:date>
                  <gmd:dateType>
                    <gmd:CI_DateTypeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_DateTypeCode" codeListValue="publication">publication</gmd:CI_DateTypeCode>
                  </gmd:dateType>
                </gmd:CI_Date>
              </gmd:date>

            </gmd:CI_Citation>
          </gmd:thesaurusName>
        </gmd:MD_Keywords>
      </gmd:descriptiveKeywords>


Freie Schlagwörter
''''''''''''''''''
      <gmd:descriptiveKeywords>
        <gmd:MD_Keywords>
          <gmd:keyword>
            <gco:CharacterString>ST</gco:CharacterString>
          </gmd:keyword>
          <gmd:keyword>
            <gco:CharacterString>ALKIS</gco:CharacterString>
          </gmd:keyword>
          <gmd:keyword>
            <gco:CharacterString>Amtliches Liegenschaftskatasterinformationssystem</gco:CharacterString>
          </gmd:keyword>
          <gmd:keyword>
            <gco:CharacterString>Geographical Names</gco:CharacterString>
          </gmd:keyword>
        </gmd:MD_Keywords>
      </gmd:descriptiveKeywords>


Keyword inspireidentifiziert
''''''''''''''''''''''''''''
      <gmd:descriptiveKeywords>
        <gmd:MD_Keywords>
          <gmd:keyword>
            <gco:CharacterString>inspireidentifiziert</gco:CharacterString>
          </gmd:keyword>
        </gmd:MD_Keywords>
      </gmd:descriptiveKeywords>

Keyword AdVMIS
''''''''''''''
      <gmd:descriptiveKeywords>
        <gmd:MD_Keywords>
          <gmd:keyword>
            <gco:CharacterString>AdVMIS</gco:CharacterString>
          </gmd:keyword>
        </gmd:MD_Keywords>
      </gmd:descriptiveKeywords>


      <gmd:descriptiveKeywords>
        <gmd:MD_Keywords>
          <gmd:keyword>
            <gmx:Anchor xlink:href="http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/regional">Regional</gmx:Anchor>
          </gmd:keyword>
          <gmd:thesaurusName>
            <gmd:CI_Citation>

              <gmd:title>
                <gmx:Anchor xlink:href="http://inspire.ec.europa.eu/metadata-codelist/SpatialScope">Spatial scope</gmx:Anchor>
              </gmd:title>

              <gmd:date>
                <gmd:CI_Date>

                  <gmd:date>
                    <gco:Date>2019-05-22</gco:Date>
                  </gmd:date>

                  <gmd:dateType>
                    <gmd:CI_DateTypeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_DateTypeCode" codeListValue="publication">publication</gmd:CI_DateTypeCode>
                  </gmd:dateType>

                </gmd:CI_Date>
              </gmd:date>
            </gmd:CI_Citation>
          </gmd:thesaurusName>
        </gmd:MD_Keywords>
      </gmd:descriptiveKeywords>



      <gmd:resourceConstraints>
        <gmd:MD_LegalConstraints>

Nutzungsbedigungen
''''''''''''''''''  
          <gmd:useConstraints>
            <gmd:MD_RestrictionCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_RestrictionCode" codeListValue="otherRestrictions"/>
          </gmd:useConstraints>

        
          <gmd:otherConstraints>
            <gco:CharacterString>&lt;a href="https://www.lvermgeo.sachsen-anhalt.de/de/datei/anzeigen/id/3567,501/nutzungsbedingungen_b.pdf"&gt;Nutzungsbedingungen für das amtliche Vermessungswesen Sachsen-Anhalt&lt;/a&gt;</gco:CharacterString>
          </gmd:otherConstraints>

          <gmd:otherConstraints>
            <gco:CharacterString>&lt;a href="http://www.landesrecht.sachsen-anhalt.de/jportal/?quelle=jlink&amp;query=VermKostV+ST&amp;psml=bssahprod.psml&amp;max=true&amp;aiz=true"&gt;Kostenverordnung für das amtliche Vermessungswesen Sachsen-Anhalt&lt;/a&gt;</gco:CharacterString>
          </gmd:otherConstraints>

        </gmd:MD_LegalConstraints>
      </gmd:resourceConstraints>


      <gmd:resourceConstraints>
        <gmd:MD_LegalConstraints>
          <gmd:accessConstraints>
            <gmd:MD_RestrictionCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_RestrictionCode" codeListValue="otherRestrictions">otherRestrictions</gmd:MD_RestrictionCode>
          </gmd:accessConstraints>

Zugriffsbeschränkungen
''''''''''''''''''''''          
          <gmd:otherConstraints>
            <gmx:Anchor xlink:href="http://inspire.ec.europa.eu/metadata-codelist/LimitationsOnPublicAccess/noLimitations">Es gelten keine Zugriffsbeschränkungen</gmx:Anchor>
          </gmd:otherConstraints>

        </gmd:MD_LegalConstraints>
      </gmd:resourceConstraints>


Digitale Repräsentation
'''''''''''''''''''''''
      <gmd:spatialRepresentationType>
        <gmd:MD_SpatialRepresentationTypeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_SpatialRepresentationTypeCode" codeListValue="vector"/>
      </gmd:spatialRepresentationType>

    
      <gmd:spatialResolution>
        <gmd:MD_Resolution>
          <gmd:equivalentScale>
            <gmd:MD_RepresentativeFraction>
              <gmd:denominator>
                <gco:Integer>1000</gco:Integer>
              </gmd:denominator>
            </gmd:MD_RepresentativeFraction>
          </gmd:equivalentScale>
        </gmd:MD_Resolution>
      </gmd:spatialResolution>

Sprache
'''''''
      <gmd:language>
        <gmd:LanguageCode codeList="http://www.loc.gov/standards/iso639-2/" codeListValue="ger"/>
      </gmd:language>

Raumbezug
^^^^^^^^^
      <gmd:topicCategory>
        <gmd:MD_TopicCategoryCode>location</gmd:MD_TopicCategoryCode>
      </gmd:topicCategory>

      <gmd:extent>
        <gmd:EX_Extent>

          <gmd:geographicElement>
            <gmd:EX_GeographicDescription>

              <gmd:extentTypeCode>
                <gco:Boolean>true</gco:Boolean>
              </gmd:extentTypeCode>

 Geothesaurus-Raumbezug
 ''''''''''''''''''''''
              <gmd:geographicIdentifier>
                <gmd:MD_Identifier>
                  <gmd:code>
                    <gco:CharacterString>Sachsen-Anhalt</gco:CharacterString>
                  </gmd:code>
                </gmd:MD_Identifier>

              </gmd:geographicIdentifier>
            </gmd:EX_GeographicDescription>
          </gmd:geographicElement>

Boundingbox
'''''''''''
          <gmd:geographicElement>
            <gmd:EX_GeographicBoundingBox>
              <gmd:extentTypeCode>
                <gco:Boolean>true</gco:Boolean>
              </gmd:extentTypeCode>
              <gmd:westBoundLongitude>
                <gco:Decimal>10.526374</gco:Decimal>
              </gmd:westBoundLongitude>
              <gmd:eastBoundLongitude>
                <gco:Decimal>13.309751</gco:Decimal>
              </gmd:eastBoundLongitude>
              <gmd:southBoundLatitude>
                <gco:Decimal>50.972317</gco:Decimal>
              </gmd:southBoundLatitude>
              <gmd:northBoundLatitude>
                <gco:Decimal>53.060074</gco:Decimal>
              </gmd:northBoundLatitude>
            </gmd:EX_GeographicBoundingBox>
          </gmd:geographicElement>

        </gmd:EX_Extent>
      </gmd:extent>

    </gmd:MD_DataIdentification>
  </gmd:identificationInfo>



  <gmd:distributionInfo>
    <gmd:MD_Distribution>

      <gmd:distributionFormat>
        <gmd:MD_Format>
          <gmd:name>
            <gco:CharacterString>GML</gco:CharacterString>
          </gmd:name>
          <gmd:version>
            <gco:CharacterString>3.2</gco:CharacterString>
          </gmd:version>
        </gmd:MD_Format>
      </gmd:distributionFormat>


      <gmd:transferOptions>
        <gmd:MD_DigitalTransferOptions>
          <gmd:onLine>
            <gmd:CI_OnlineResource>
              <gmd:linkage>
                <gmd:URL>https://www.lvermgeo.sachsen-anhalt.de/de/kostenfreie_geobasisdaten_lvermgeo.html</gmd:URL>
              </gmd:linkage>
              <gmd:name>
                <gco:CharacterString>Kostenfreie Geobasisdaten LVermGeo</gco:CharacterString>
              </gmd:name>
              <gmd:function>
                <gmd:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_OnLineFunctionCode" codeListValue="information">information</gmd:CI_OnLineFunctionCode>
              </gmd:function>
            </gmd:CI_OnlineResource>
          </gmd:onLine>
        </gmd:MD_DigitalTransferOptions>
      </gmd:transferOptions>


      <gmd:transferOptions>
        <gmd:MD_DigitalTransferOptions>
          <gmd:onLine>
            <gmd:CI_OnlineResource>
              <gmd:linkage>
                <gmd:URL>https://www.lvermgeo.sachsen-anhalt.de/de/datei/anzeigen/id/13853,501/gebuehren_bereitstellung_weiterverwendung_inspire_b.pdf</gmd:URL>
              </gmd:linkage>
              <gmd:name>
                <gco:CharacterString>Gebühren der INSPIRE-konformen Geodatendienste</gco:CharacterString>
              </gmd:name>
              <gmd:function>
                <gmd:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_OnLineFunctionCode" codeListValue="information">information</gmd:CI_OnLineFunctionCode>
              </gmd:function>
            </gmd:CI_OnlineResource>
          </gmd:onLine>
        </gmd:MD_DigitalTransferOptions>
      </gmd:transferOptions>


      <gmd:transferOptions>
        <gmd:MD_DigitalTransferOptions>
          <gmd:onLine>
            <gmd:CI_OnlineResource>
              <gmd:linkage>
                <gmd:URL>https://www.geodatenportal.sachsen-anhalt.de/wss/service/INSPIRE_LVermGeo_WFS_ALKIS_GN/guest</gmd:URL>
              </gmd:linkage>
              <gmd:name>
                <gco:CharacterString>Dienst "INSPIRE-WFS ST Geografische Bezeichnungen ALKIS" (GetCapabilities)</gco:CharacterString>
              </gmd:name>
              <gmd:function>
                <gmd:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_OnLineFunctionCode" codeListValue="information">information</gmd:CI_OnLineFunctionCode>
              </gmd:function>
            </gmd:CI_OnlineResource>
          </gmd:onLine>
        </gmd:MD_DigitalTransferOptions>
      </gmd:transferOptions>


      <gmd:transferOptions>
        <gmd:MD_DigitalTransferOptions>
          <gmd:onLine>
            <gmd:CI_OnlineResource>
              <gmd:linkage>
                <gmd:URL>https://www.geodatenportal.sachsen-anhalt.de/wss/service/INSPIRE_LVermGeo_ALKIS_GN/guest</gmd:URL>
              </gmd:linkage>
              <gmd:name>
                <gco:CharacterString>Dienst "INSPIRE-WMS ST Geografische Bezeichnungen ALKIS" (GetCapabilities)</gco:CharacterString>
              </gmd:name>
              <gmd:function>
                <gmd:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_OnLineFunctionCode" codeListValue="information">information</gmd:CI_OnLineFunctionCode>
              </gmd:function>
            </gmd:CI_OnlineResource>
          </gmd:onLine>
        </gmd:MD_DigitalTransferOptions>
      </gmd:transferOptions>


    </gmd:MD_Distribution>
  </gmd:distributionInfo>

  <gmd:dataQualityInfo>
    <gmd:DQ_DataQuality>
      <gmd:scope>
        <gmd:DQ_Scope>
          <gmd:level>
            <gmd:MD_ScopeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#MD_ScopeCode" codeListValue="dataset"/>
          </gmd:level>
        </gmd:DQ_Scope>
      </gmd:scope>
      
      <gmd:report>
        <gmd:DQ_DomainConsistency>
          <gmd:result>
            <gmd:DQ_ConformanceResult>
              <gmd:specification>
                <gmd:CI_Citation>

                  <gmd:title>
                    <gco:CharacterString>VERORDNUNG (EG) Nr. 1089/2010 DER KOMMISSION vom 23. November 2010 zur Durchführung der Richtlinie 2007/2/EG des Europäischen Parlaments und des Rates hinsichtlich der Interoperabilität von Geodatensätzen und -diensten</gco:CharacterString>
                  </gmd:title>

                  <gmd:date>
                    <gmd:CI_Date>
                      <gmd:date>
                        <gco:Date>2010-12-08</gco:Date>
                      </gmd:date>
                      <gmd:dateType>
                        <gmd:CI_DateTypeCode codeList="http://standards.iso.org/iso/19139/resources/gmxCodelists.xml#CI_DateTypeCode" codeListValue="publication">publication</gmd:CI_DateTypeCode>
                      </gmd:dateType>
                    </gmd:CI_Date>
                  </gmd:date>
                </gmd:CI_Citation>
              </gmd:specification>

              <gmd:explanation>
                <gco:CharacterString>see the referenced specification</gco:CharacterString>
              </gmd:explanation>

              <gmd:pass>
                <gco:Boolean>true</gco:Boolean>
              </gmd:pass>

            </gmd:DQ_ConformanceResult>
          </gmd:result>
        </gmd:DQ_DomainConsistency>
      </gmd:report>


      <gmd:lineage>
        <gmd:LI_Lineage>
          <gmd:statement>
            <gco:CharacterString>Abgeleitet aus ALKIS</gco:CharacterString>
          </gmd:statement>
        </gmd:LI_Lineage>
      </gmd:lineage>
    </gmd:DQ_DataQuality>
  </gmd:dataQualityInfo>

</gmd:MD_Metadata>