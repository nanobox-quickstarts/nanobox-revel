![Revel from scratch](https://guides.nanobox.io/assets/quickstart-icons/revel.png)

# Revel from scratch

Run a Revel app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>

## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-revel.git

# cd into the revel app
cd nanobox-revel
```

## Run the app

```bash
# Run Revel as you would normally, with Nanobox
nanobox run revel run nanobox-revel
```

## Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local revel.dev
```

Visit your app at <a href="http://revel.dev:9000" target="\_blank">revel.dev:9000</a>

## Explore
With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where golang is installed,
go version

# git is installed,
git -v

# and your code is mounted
ls
```

## Now What?
For more details about running Revel apps with nanobox visit [guides.nanobox.io/golang/revel/](https://guides.nanobox.io/golang/revel/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
