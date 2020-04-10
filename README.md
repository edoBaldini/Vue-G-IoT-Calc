# (VUE) Green IoT impacts calculator

 <img src="/Users/edoardobaldiniicloud.com/Workspace/G-IoT-Web-Service/vue-g-iot-calc/readme-images/IotLandscape.pdf" alt="BootstrapVue" style="zoom:300%;" />

Green IoT is defined as energy-efficient procedures adopted by IoT either to reduce the GHGE of existing applications or to reduce the impact of IoT itself. In the literature there are many strategies that allow to reduce the impact of these devices at each stage of their lifecycle but what is missing is a way to estimate how green an IoT solution is.

The model proposed in my thesis work is one of the first attempts to assess the energy required and waste produced by the devices employed in an IoT solution  focusing on outdoor application equipped with an energy harvesting solution.

The following project represents the frontend of the web service developed as part of my master thesis work.

The aim of the web service is to estimate the energy impact (expressed in MJ) and the waste impact (expressed in Kg) of the user's IoT solution. The service finally returns the ratio between the impacts of the evaluated solution and a greener one that is computed by the web service.

In order to evaluate the impacts, the service needs some information about the user's IoT solution. For this purpose a simple and easy understanding frontend has been developed. 

The web page is based on a 5-steps input-form and then, as last step, it shows through graphs the impacts of the client solution and the comparison with the greenest one. 

Additional information about the webservice can be found in the dedicated repository: https://github.com/edoBaldini/Rest-G-IoT-Calc-API

## Installing	

```
mkdir vue-g-iot-calc
cd vue-g-iot-calc
npm install -g @vue/cli@3.7.0
vue init webpack .
```

> - Generate project in current directory ```Yes```
> - Project name ``` vue-g-iot-calc```
> - Project decription ```A Vue,js project```
> - Author ```Edoardo```
> - Vue build ```standalone```
> - Install vue-router? ```Yes```
> - Use ESLint to lint yout code? ```Yes```
> - Pick an ESLint preset ```Airbnb```
> - Set up unit tests ```No```
> - Should we run 'nom install' for you after the project has been created? ```npm```

```
git clone https://github.com/edoBaldini/vue-g-iot-calc.git temp
cp -a ./temp/ ./
rm -rf temp
npm install
npm audit fix
```

to run the frontend:

```
npm run dev
```

to stop it:

```control + c```

## Build with

- <a haref="https://bootstrap-vue.js.org/">Bootstrap-Vue</a> <img src="/Users/edoardobaldiniicloud.com/Workspace/G-IoT-Web-Service/vue-g-iot-calc/readme-images/BootstrapVue.png" alt="BootstrapVue" style="zoom:10%;" />
- <a href="https://www.chartjs.org/">Chart.js</a><img src="/Users/edoardobaldiniicloud.com/Workspace/G-IoT-Web-Service/vue-g-iot-calc/readme-images/chartjs-logo.svg" alt="chartjs-logo" style="zoom:25%;" />
- <a href="https://www.npmjs.com/package/vue-json-pretty">Json-pretty</a>
- <a href="https://github.com/vue-generators/vue-form-generator">Vue-form-generator</a>
- <a href="https://github.com/BinarCode/vue-form-wizard">Vue-form-wizard</a>
- <a href="https://www.npmjs.com/package/vue-videobg">Vue-videobg</a>