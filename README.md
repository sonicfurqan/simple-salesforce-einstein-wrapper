# simple-salesforce-einstein-wrapper
Pre-requisites 

  1.regester youreself on https://api.einstein.ai/signup and download einstein_platform.pem
  2.upload einstein_platform.pem in your org
  3.create a label of name EinsteinAI_BaseUrl and enter you email address using which you have registered

Use:
  For Language
    1.create an instance of EinsteinAI_Language and then call methods to build dataset,train dataset,predict dataset..etc

    Example
    EinsteinAI_Language service=new EinsteinAI_Language();
    service.getApiUsage();

  For Vison
    1.create an instance of EinsteinAI_Vision and then call methods to build dataset,train dataset,predict dataset..etc

    Example
    EinsteinAI_Vision service=new EinsteinAI_Vision();
    service.getApiUsage();
