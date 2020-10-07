# python-selenium-requests-BeautifulSoup
contains project regarding python selenium requests and BeautifulSoup

installation guide for BeautifulSoup https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup










## TO configure header only the you need
#### even if we configure headers request library addsup some default headers
#### by this method python request library wo't sent any other header then the specified
url = "https://github.com/api"
headers = {"Content-Type": "application/json;charset=UTF-8",
               "Connection": "close"}
req = Request('POST', url,
              json=data, headers=headers)
prepped = req.prepare()
r = self.session.send(prepped, verify=False)
ress = r.json()
