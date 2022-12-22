# FlogoAppSorter
The Repo consists of a flogo app json which can take in unsorted complex data and sort it based on one of its component

It also has a sample flow associated with it to understand how it works by the name <b>Sorter Example</b>

Following is an Example 

Input Array
{
  "root": {
    "elementToSortOver": "success",
    "rootArray": [
      {
        "appId": "os44ceaecrqz6vscwgpyrbwqj7iwgqax",
        "appName": "Sample-CI-V1-DEV",
        "failure": 0,
        "success": 1030
      },
      {
        "appId": "uhcvaoee5p5dnvgtpkirdkr63gxbjtlo",
        "appName": "Sample-AI-V1-DEV",
        "failure": 0,
        "success": 388
      },
      {
        "appId": "bhiacb2gn6zgvn5lslfkwkbi45nishrn",
        "appName": "Sample-DI-V1-DEV",
        "failure": 0,
        "success": 0
      },
      {
        "appId": "hnuomtk6cqmqzwbmnnz6n3xvbj3rp5eu",
        "appName": "Sample-EI-V1-DEV",
        "failure": 0,
        "success": 4
      },
      {
        "appId": "sww7zzwgljewtxxy7yydtiqb74gwjtoe",
        "appName": "Sample-FI-V1-DEV",
        "failure": 0,
        "success": 0
      },
      {
        "appId": "pd5atavhbcc63gn3bevb3o2bauqkoqm4",
        "appName": "Sample-GI-V1-DEV",
        "failure": 0,
        "success": 864
      },
      {
        "appId": "jyqv75douamv2ieaogqxqtstpqmcwsio",
        "appName": "Sample-HI-V1-DEV",
        "failure": 0,
        "success": 27
      },
      {
        "appId": "dbo6easmljtqx2yc6rwwrtosfy3hmv34",
        "appName": "Sample-I-V1-DEV",
        "failure": 0,
        "success": 0
      },
      {
        "appId": "3jzmm3ibiaj2mtuxlijdgoscclskmuju",
        "appName": "Sample-JI-V1-DEV",
        "failure": 0,
        "success": 0
      },
      {
        "appId": "3hrkc4ycpsgeimnt2geinj3bjlzpvrcf",
        "appName": "Sample-KI-V1-DEV",
        "failure": 0,
        "success": 790
      }
    ]
  }
}



Output 
{
  "root": {
    "rootArray": [
      {
        "appId": "os44ceaecrqz6vscwgpyrbwqj7iwgqax",
        "appName": "Sample-CI-V1-DEV",
        "failure": 0,
        "success": 1030
      },
      {
        "appId": "pd5atavhbcc63gn3bevb3o2bauqkoqm4",
        "appName": "Sample-GI-V1-DEV",
        "failure": 0,
        "success": 864
      },
      {
        "appId": "3hrkc4ycpsgeimnt2geinj3bjlzpvrcf",
        "appName": "Sample-KI-V1-DEV",
        "failure": 0,
        "success": 790
      },
      {
        "appId": "uhcvaoee5p5dnvgtpkirdkr63gxbjtlo",
        "appName": "Sample-AI-V1-DEV",
        "failure": 0,
        "success": 388
      },
      {
        "appId": "jyqv75douamv2ieaogqxqtstpqmcwsio",
        "appName": "Sample-HI-V1-DEV",
        "failure": 0,
        "success": 27
      },
      {
        "appId": "hnuomtk6cqmqzwbmnnz6n3xvbj3rp5eu",
        "appName": "Sample-EI-V1-DEV",
        "failure": 0,
        "success": 4
      },
      {
        "appId": "sww7zzwgljewtxxy7yydtiqb74gwjtoe",
        "appName": "Sample-FI-V1-DEV",
        "failure": 0,
        "success": 0
      },
      {
        "appId": "dbo6easmljtqx2yc6rwwrtosfy3hmv34",
        "appName": "Sample-I-V1-DEV",
        "failure": 0,
        "success": 0
      },
      {
        "appId": "3jzmm3ibiaj2mtuxlijdgoscclskmuju",
        "appName": "Sample-JI-V1-DEV",
        "failure": 0,
        "success": 0
      },
      {
        "appId": "bhiacb2gn6zgvn5lslfkwkbi45nishrn",
        "appName": "Sample-DI-V1-DEV",
        "failure": 0,
        "success": 0
      }
    ]
  }
}

Please Note : It sorts in descing order if required to get in ascending do array.reverse()

Advantages
Does not require any external go module downloaded to work with it

Limitation
For now it can sort on number data only 

Feel free to use it in your flows 
Citation is appreciated but not required :) 
Hope it helps anyone who uses it 
