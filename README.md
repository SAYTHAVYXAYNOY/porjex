# porjex kieem tra wep ban xe o to
#https://bonbanh.com/khanh-hoa/oto
{
  "id": "f7cd8634-e93f-45de-bfe3-447ff80ef9a2",
  "version": "2.0",
  "name": "ban xe",
  "url": "https://bonbanh.com/khanh-hoa/oto",
  "tests": [{
    "id": "2bb8bb0c-fc24-4847-a4b7-2de6c406d5a9",
    "name": "Bán xe ô tô",
    "commands": [{
      "id": "2a71b2da-458b-45b5-b595-54b7281cda02",
      "comment": "",
      "command": "open",
      "target": "https://bonbanh.com/khanh-hoa/oto",
      "targets": [],
      "value": ""
    }, {
      "id": "4e2f6ea0-a479-4628-ad30-0c3af9af93e4",
      "comment": "",
      "command": "setWindowSize",
      "target": "782x823",
      "targets": [],
      "value": ""
    }, {
      "id": "db7e4045-9afc-4b06-bc14-12d284db3aa0",
      "comment": "",
      "command": "click",
      "target": "css=.car-item:nth-child(1) .h-car-img",
      "targets": [
        ["css=.car-item:nth-child(1) .h-car-img", "css:finder"],
        ["xpath=//img[@alt='Bán xe MG RX5 2024 1.5T STD giá 619 Triệu - Khánh Hòa']", "xpath:img"],
        ["xpath=//div[@id='s-list-car']/div/ul/li/a/div[5]/span/img", "xpath:idRelative"],
        ["xpath=//div[5]/span/img", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f69d8a06-b9a8-4e1e-8a8b-44a8c4f8e3c0",
      "comment": "",
      "command": "runScript",
      "target": "window.scrollTo(0,100)",
      "targets": [],
      "value": ""
    }, {
      "id": "26225235-0f60-4fa0-94bd-2a439e7ad4b3",
      "comment": "",
      "command": "click",
      "target": "css=.car-item:nth-child(6) .cb6_02",
      "targets": [
        ["css=.car-item:nth-child(6) .cb6_02", "css:finder"],
        ["xpath=//div[@id='s-list-car']/div/ul/li[6]/a/div[6]", "xpath:idRelative"],
        ["xpath=//li[6]/a/div[6]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "4b62f968-a046-4647-a02b-b1f3059a8861",
      "comment": "",
      "command": "click",
      "target": "css=.car-item:nth-child(18) .cb6_02",
      "targets": [
        ["css=.car-item:nth-child(18) .cb6_02", "css:finder"],
        ["xpath=//div[@id='s-list-car']/div/ul/li[18]/a/div[6]", "xpath:idRelative"],
        ["xpath=//li[18]/a/div[6]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "179a5c51-f6aa-43f4-a4ef-5bdba4036e8b",
      "comment": "",
      "command": "click",
      "target": "css=.car-item:nth-child(20) .h-car-img",
      "targets": [
        ["css=.car-item:nth-child(20) .h-car-img", "css:finder"],
        ["xpath=//img[@alt='Bán xe Mercedes Benz GLC 2023 200 4Matic giá 2 Tỷ 184 Triệu - Khánh Hòa']", "xpath:img"],
        ["xpath=//div[@id='s-list-car']/div/ul/li[20]/a/div[5]/span/img", "xpath:idRelative"],
        ["xpath=//li[20]/a/div[5]/span/img", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "0a620db0-cf91-4279-99f4-3185bb567b17",
      "comment": "",
      "command": "runScript",
      "target": "window.scrollTo(0,100)",
      "targets": [],
      "value": ""
    }, {
      "id": "b2498f42-9330-4980-ae53-60b6527dbbd3",
      "comment": "",
      "command": "runScript",
      "target": "window.scrollTo(0,0)",
      "targets": [],
      "value": ""
    }]
  }],
  "suites": [{
    "id": "19940574-2a41-4e9f-b2da-9e24e92034d4",
    "name": "Default Suite",
    "persistSession": false,
    "parallel": false,
    "timeout": 300,
    "tests": ["2bb8bb0c-fc24-4847-a4b7-2de6c406d5a9"]
  }],
  "urls": [],
  "plugins": []
}
