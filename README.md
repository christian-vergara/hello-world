# hello-world

package p1;

public class Address {

	private String streetNumber, zipCode, state, city;
	
	public Address() {
		
	}
	
	public Address(String streetNumber, String zipCode, String state, String city) {
		this.streetNumber = streetNumber;
		this.zipCode = zipCode;
		this.state = state;
		this.city = city;
	}
	
	public Address(Address address) {
		super();
		this.streetNumber = address.getStreetNumber();
		this.zipCode = address.getZipCode();
		this.state = address.getState();
		this.city = address.getCity();
	}

	public String getStreetNumber() {
		return streetNumber;
	}

	public void setStreetNumber(String streetNumber) {
		this.streetNumber = streetNumber;
	}

	public String getZipCode() {
		return zipCode;
	}

	public void setZipCode(String zipCode) {
		this.zipCode = zipCode;
	}

	public String getState() {
		return state;
	}

	public void setState(String state) {
		this.state = state;
	}

	public String getCity() {
		return city;
	}

	public void setCity(String city) {
		this.city = city;
	}

	@Override
	public String toString() {
		return "Address [streetNumber=" + streetNumber + ", zipCode=" + zipCode
				+ ", state=" + state + ", city=" + city + "]";
	}
	

