from speedtest import Speedtest
internet = Speedtest()

def download_internet():
    print(f'calculating.....')
    download = internet.download()
    download = download / 1000000
    print(f'your download speed is {download} Mbit/s')

def upload_internet():
    print(f'calculating....')
    upload = internet.upload()
    upload = upload / 1000000
    print(f'your upload speed is {upload} Mbit/s')


download_internet()
upload_internet()
