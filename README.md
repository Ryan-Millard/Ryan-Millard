System.out.println("Hi, I'm Ryan Millard.👋");  
//---------------------------------------------------------------------------------------  
Console.log('I’m interested in learning as much as I can in robotics, full stack developent, and ML.🧠')  
//-----------------------------------------------------------------------------------------------------------  
Console.WriteLine(" I currently am focusing my efforts on learning embedded programming as a precursor to robotics.🤖🤖");  
  
try  
{  
  emailMe("millardryadevon@gmail.com📧");  
}  
catch(EmailNotPreferredException e)  
{  
  var socialMediaApps = { "Instagram", "X/Twitter", "Facebook", "Snapchat", "TikTok" };  
  var appsYouUse = setAppsYouUse(socialMediaApps);  
  
  for(var app : appsYouUse)  
    switch(app)  
    {  
      case "Instagram" -> System.out.println("My username on Instagram is: \"ryan.d.millard\"");  
      case "Facebook" -> System.out.println("My username on Facebook is: \"Ryan Millard\"");  
      default: -> System.out.println("Please choose another social media app.");  
      }  
}  
finally  
{  
  wishUserAGoodDay("👋👋👋");  
}  
