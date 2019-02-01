# hotel-booking

using Keys.Global;
using OpenQA.Selenium;
using OpenQA.Selenium.Support.PageObjects;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Keys.Pages
{
    public class Register
    {
        internal Register()
        {
            PageFactory.InitElements(Driver.driver, this);
        }
   }    
             //Enter FirstName
        [FindsBy(How = How.XPath, Using = "//*[@id='FirstName']")]
        private IWebElement FirstName { get; set; }
       
    //Enter LastName
        [FindsBy(How = How.XPath, Using = "//*[@id='LastName']")]
        private IWebElement LastName { get; set; }
    
   //Enter Price
        [FindsBy(How = How.XPath, Using = "//*[@id='Price']")]
        private IWebElement LastName { get; set; }
    
    //Enter Deposit
        [FindsBy(How = How.XPath, Using = "//*[@id='Deposit']")]
        private IWebElement LastName { get; set; }
    
    //Enter Check-In Date
        [FindsBy(How = How.XPath, Using = "//*[@id='Check-In']")]
        private IWebElement LastName { get; set; }
        
    //Enter Check-Out Date
        [FindsBy(How = How.XPath, Using = "//*[@id='Check-Out']")]
        private IWebElement LastName { get; set; }
    
    
        
