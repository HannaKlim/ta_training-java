# ta_training-java
## Проект по тестированию сайта
*Тестировали, тестировали, и наконец протестировали
### Использовали:
* Webdriver
* JUnit5
* RestAssured
* Google

<pre><code> 
    @When("Input word Java")
    public void inputWord(){
        By byInputField = By.xpath(xPathInputField);
        WebElement elementInputField = driver.findElement(byInputField);
        elementInputField.sendKeys("Java");
    }
</code></pre>


### П

![картинка]()
