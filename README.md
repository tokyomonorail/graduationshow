# Graduation (dot) Show

`graduationshow-data.csv` geeft een overzicht van afstudeerprojecten aan Nederlandse design-gerelateerde opleidingen uit 2019:

Academie | Plaats | Afdeling | Aantal projecten
--- | --- | --- | ---
AKV St. Joost | Breda/Den Bosch | BA Grafisch/Ruimtelijk Ontwerp | 29
ArtEZ Hogeschool voor de Kunsten | Arnhem | BA Product Design | 14
Design Academy Eindhoven | Eindhoven | MA Contextual Design, MA Design Curating and Writing, MA Information Design, MA Social Design, BA Food Non Food, BA Man and Activity, BA Man and Communication, BA Man and Identity, BA Man and Leisure, BA Man and Motion, BA Man and Well being, BA Public Private | 187
Gerrit Rietveld Academie | Amsterdam | designLAB, Architectural Design | 20
Hogeschool voor de Kunsten Tilburg | Tilburg | BA Academy of Art, Communication and Design | 14
Hogeschool voor de Kunsten Utrecht | Utrecht | BA Product Design, BA Spatial Design, BA Fashion Design, MA Interior Architecture | 82
Koninklijke Academie van Beeldende Kunsten | Den Haag | BA Graphic Design, MA Non Linear Narrative | 50
Piet Zwart Institute (Willem de Kooning Academie) | Rotterdam | MA Interior Architecture: Research + Design | 6
Sandberg Instituut (Gerrit Rietveld Academie) | Amsterdam | MA Design, MA Design of Experiences | 20
Willem de Kooning Academie | Rotterdam | BA Product Design, BA Spatial Design, BA Graphic Design, BA Lifestyle Transformation Design, BA Audiovisual Design, BA Fashion Design, MA Design | 76


De dataset is op de volgende manier georganiseerd:

Header | Inhoud
--- | ---
`titel`| Titel van het project
`url`| Link naar de originele publicatie
`inhoud`| Beschrijvende tekst
`vorm1`| Gekozen vorm
`vorm2`| Gekozen vorm (bij meerdere)
`vorm3`| Gekozen vorm (bij meerdere)
`onderwerp1`| Gekozen onderwerp
`onderwerp2`| Gekozen onderwerp (bij meerdere)
`onderwerp3`| Gekozen onderwerp (bij meerdere)
`academie`| Naam van de academie
`afdeling`| Naam van de afdeling
`graad`| Bachelor of Master
`jaar`| Afstudeerjaar

Notities:

- Alle vorm/onderwerp tags zijn geschreven in het Nederlands, ongeacht de taal van de beschrijvende tekst
- In de vorm/onderwerp kolommen staan alleen zelfstandige naamwoorden zonder lidwoord. Als het onderwerp uit meerdere woorden bestaat worden die aan elkaar geschreven. Dus 'socialemedia' in plaats van 'sociale media' en 'hetlichaam' in plaats van 'het lichaam'.
