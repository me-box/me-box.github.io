## To prepare for the day

Databox is composed of many components running as Docker containers, and so you
will need to bring a computer capable of running
[Docker](https://www.docker.com) if you wish to run Databox or do any
development. Also note that cloning our repo and running Databox for the first
time will consume approximately 2GB of data -- we ask that you please do this
before arriving at the venue to avoid overloading the Wi-Fi.

Everybody taking part in the development oriented sessions will need to install:

  * [Docker](https://docs.docker.com/engine/installation/#desktop), and
  * [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)


### Session "Hacking the core"

```bash
git clone https://github.com/me-box/databox.git
cd databox
./databox-start dev
```

In a different terminal
```bash
./databox-install-component driver-os-monitor
```

### Session "Building an app with the SDK"

```bash
git clone https://github.com/me-box/databox.git
cd databox
./databox-start sdk
```

In a different terminal
```bash
./databox-install-component driver-os-monitor
```

### Session "Building apps with Python"

```bash
git clone https://github.com/me-box/databox.git
cd databox
./databox-start
```

In a different terminal
```bash
./databox-install-component driver-os-monitor
```

## Social

If you are interested in attending dinner after the event please let [Dr John
Moore](mailto:jm2170@cl.cam.ac.uk) from the Databox team know during lunch to
allow time to book a table at the restaurant. Unfortunately the project is
unable to cover the costs of dinner so attendees will need to pay individually.
