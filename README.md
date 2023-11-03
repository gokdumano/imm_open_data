# Example Package

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.

Here is a simple flow chart:

```mermaid
graph TD;
    immopendata-->havakalitesi.py;
    immopendata-->iett.py;
    immopendata-->isbike.py;
    immopendata-->ispark.py;
    immopendata-->istac.py;
    havakalitesi.py-->GetAQIStations;
    havakalitesi.py-->GetAQIByStationId;
    iett.py-->GetStopByCode;
    iett.py-->GetAllGarages;
    iett.py-->GetAnnouncements;
    iett.py-->GetBadRoads;
    iett.py-->GetAccidentsByDate;
    iett.py-->GetLineStopsByCode;
    iett.py-->GetLineDetails;
    isbike.py-->GetStationStatus;
    isbike.py-->GetAllStationStatus;
    ispark.py-->GetAllParks;
    ispark.py-->GetParkDetail;
    istac.py-->GetTotalWeightByYear;
```
```mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```
