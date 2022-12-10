package page_object;

import java.util.List;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;

public class LoginPageObject {

	public WebDriver driver;
	
	private By username_field = By.xpath("//input[@name='username']");
	private By password_field = By.xpath("//input[@name='password']");
	private By login_submit = By.xpath("//button[@type='submit']");
	private By required_fields_alert = By.cssSelector("div.orangehrm-login-form > form > div.oxd-form-row > div");
	private By invalid_credentials_alert = By.cssSelector("div.orangehrm-login-form > div.orangehrm-login-error > div.oxd-alert--error > div > p");
	private By forgot_password_link = By.cssSelector("div.orangehrm-login-form > form > div.orangehrm-login-forgot");
	
	public LoginPageObject(WebDriver driver) {
		// TODO Auto-generated constructor stub
		this.driver = driver;
	}

	public WebElement get_username_field() {
		return driver.findElement(username_field);
	}
	
	public WebElement get_password_field() {
		return driver.findElement(password_field);
	}
	
	public WebElement get_login_submit() {
		return driver.findElement(login_submit);
	}
	
	public List <WebElement> get_required_fields_alert(){
		return driver.findElements(required_fields_alert);
	}
	
	public WebElement get_alert_field() {
		return driver.findElement(invalid_credentials_alert);
	}
	
	public WebElement get_forgot_password_link() {
		return driver.findElement(forgot_password_link);
	}
}
