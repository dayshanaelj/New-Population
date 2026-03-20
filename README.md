
/*Description: 
*I am creating a class that is extended to the LocatedPlace class so that is able to access the.
*variables set in there along with the new variable Population.    
*Author: Dayshanae Johnson 
*Modified: 02/10/2022
*/

public class PopulatedPlace extends LocatedPlace {

    // this holds everything

//this is three

    protected String Population;

    public PopulatedPlace(String Zip, String City, String State, String Longitude, String Latitude, String Population) {

        // super method calling the methods within the LocatedPlace

        super(Zip,City,State, Longitude,Latitude);
        this.Population = Population;

    }

    // this constructor is returning the toString method
    // which returns the townName and stateName
    public String toString() {
        // Two string method that returns
        return   this.zipCode + " " + this.cityName + " " + this.stateName + " " + this.longitude + " " + this.latitude + "" + this.Population;
    }

    // accessor methods that get zipCode
    public String getzipCode() {

        return  super.getzipCode();
    }

    // This constructor is setting the zipcode
    public void setZipCode(String zipCode) {

        this.zipCode = zipCode;
    }

    // accessor methed that gets townName
    public String getCityName() {

        return super.cityName;
    }

    // This constructor is setting the townName
    public void setCityName(String CityName) {

        this.cityName = CityName;
    }

    // accessor method that gets stateName
    public String getstateName() {
        // state abreviation
        return  super.stateName;
    }

    // This constructor is setting the stateName
    public void setStateName(String stateName) {
        this.stateName = stateName;
    }

    public String getLat(String latitude) {

        return latitude;
    }

    public void setLat(String latitude) {
        this.latitude = latitude;
    }

    public String getLong(String longitude) {

        return longitude;
    }

    public void setLong(String longitude) {

        this.longitude = longitude;
    }

    
    public String getPopulation(String Population) {

        return Population;
    }

    public void setPopulation(String Population) {

        this.Population = Population;
        }
            
    }
