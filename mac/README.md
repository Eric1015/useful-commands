- to allow any softwares to be installed on mac

```
sudo spctl --master-disable
```
- To enable again (Remember to do this after installing the software)
```
sudo spctl --master-enable
```

- To list what is running on the port that you are interested in:
```
sudo lsof -i -P -n | grep <port_number>
```
