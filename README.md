# Arras Energy - Public Website
This the public website https://arras-energy.github.io/static-website/ for commerical release of Arras Energy, formerly known as HiPAS GridLab-D. 

Arras Energy is a robust open-source simulation platform designed to address the evolving challenges of electricity distribution power systems in the context of smart grids and renewable energy integration. This platform serves as a valuable tool for utilities, researchers, and technology vendors, enabling them to develop, refine, and deploy advanced solutions in the domain of smart-grid technologies and renewable energy integration. 

Feel free to add and edit content to this website!
________

**Home Page**
<img width="1432" alt="Home Page" src="https://github.com/arras-energy/static-website/assets/128001866/b40d2a20-5089-4731-b540-3d0726cb59d9">

<br/>

**Content Page**

<img width="1429" alt="Content Page" src="https://github.com/arras-energy/static-website/assets/128001866/20141b34-05ae-422d-9f4a-bdf2348635a0">

<br/>

**Menu Bar**
<img width="1427" alt="Menu Bar" src="https://github.com/arras-energy/static-website/assets/128001866/9fd84fe4-1a92-4340-ae67-267714adff1a">

<br/>

## Getting Started

Whether you are a user or a developer, Arras Energy offers comprehensive resources to facilitate your journey into the world of advanced electricity distribution power systems simulation. This website hosts the following:
- **[Tutorials](https://arras-energy.github.io/static-website/tutorials/)**: Learn the ins and outs of Arras Energy with our curated collection of video presentations and slide guides. Whether you're an entry-level user or an adept developer, our resources cater to all skill levels.
- **[Use-Cases](https://arras-energy.github.io/static-website/use-cases/)**: Explore the success stories of Arras Energy's implementation in real-world scenarios. Dive into use-cases spanning diverse areas such as solar and batteries (ICA), resilience in the face of wildfires and storms, innovative tariff and billing structures, and the realization of a greener planet through electrification.
- **[Reports](https://arras-energy.github.io/static-website/literature/)**: Delve into in-depth literature and stay updated with news articles related to the advancements and applications of Arras Energy in the field of electricity distribution power systems.

## How To Maintain Website Content

### Deployment

There are several alternatives to building and deploying the site:

1. build the site with [GitHub Arras Energy Public Site]([https://github.com/features/actions](https://github.com/arras-energy/static-website)) to build pages and run actions
to the *basic-site* branch. This is the approach that is currently used. 

2. generate the site locally by opening your code editing software's terminal and run

```sh
bundle exec jekyll serve --livereload
```
and cmd select "server adress:" to veiw the live site while you edit. Then push the resulting
HTML to a Github repository, that GitHub Pages then host;

3. commit and push all changes through GitHub desk top or using the code editing terminal 

For option **2)** simply clone this repository (*master branch*), and then run
`bundle exec jekyll serve` inside the directory. Upload the resulting `_site/` (or `../static-website-pages/`)
contents to your repository (*master branch* if uploading as your personal page
(e.g. username.github.io) 

For option **3)** you will need to set up travis-ci for your personal fork. Briefly all you
need then is to change your details in *[\_config.yml](_config.yml)* so that you can push
to your github repo. You will also need to generate a secure key to add to your
*[.travis.yml](.travis.yml)* (you can find more info on how to do it in that file).
This approach has clear
advantages in that you simply push your file changes to GitHub and all the HTML files
are generated for you and pushed to *gh-pages*. 

### Adding Content Pages

In order to properly generate Content pages you need to create a new file and add a index.md file with the tab *name* as defined in the *[\_config.yml](_config.yml)* file. Make sure to page details to the top. 

```sh
---
layout: page
cover: 'assets/images/close.jpg'
title: Enter your title here
navigation: true
logo: 'assets/images/arras.png'
current: about
---
```

## Run on GitHub
<img width="1428" alt="GitHub Pages" src="https://github.com/arras-energy/static-website/assets/128001866/088211f7-1bed-4bc5-9805-c031a08de475">

You can run Arras Energy with GitHub Actions using the template https://github.com/gridlabd-tutorials/.new_project. The simulation results are stored in a downloadable file that can accessed from the ```Actions``` tab in your GitHub project. A tutorial for using Arras Energy with GitHub is available at https://github.com/gridlabd-tutorials.

## Run on Docker

To run a GridLAB-D simulation using Docker, follow these steps:

1. Open your terminal or command prompt.

2. Navigate to the directory where your GridLAB-D model file is located.

3. Use the following Docker command to run the simulation:

```sh
docker run -it -v $PWD:/model slacgismo/gridlabd:latest gridlabd -W /model [LOADOPTIONS] [FILENAME.EXT] [RUNOPTIONS]
```

See [Dockerhub HiPAS](https://hub.docker.com/r/hipas/gridlabd/tags) repositories for a list of available images.

## Run on AWS
1. Sign into your AWS console.
2. Launch an EC2 instance.
3. Search the community AMI for images starting with gridlabd in the us-west-1 (N. California) region.
4. Choose an instance type with sufficient memory, e.g., >4GB.
5. Download and save your keypair.
6. Launch the instance.
7. Connect to the instance.
8. Download your model into the instance, e.g., from GitHub.
9. Run the simulation using the usual command line options.
10. Save the results, e.g., to GitHub.

You can also start the instance from the command line:
```sh
aws ec2 run-instances --image-id AMINAME --count 1 --instance-type INSTANCETYPE --key-name KEYPAIRNAME --security-group-ids SECURITYGROUPID --subnet-id SUBNETID
```

You can search the [AWS AMI Catalog](https://us-west-1.console.aws.amazon.com/ec2/home?AMICatalog%3A=&region=us-west-1#AMICatalog:) for Community AMIs matching "Arras Energy HiPAS GridLAB-D" in the us-west-1 region. The version number will be included in the name.

## Download on Mac, Windows WSL, or Ubuntu Linux
```sh
curl -sL https://install.gridlabd.us/install.sh | [sudo] sh
```

## Build your own
```sh
git clone https://source.gridlabd.us/ [-b BRANCH] gridlabd
cd gridlabd
./setup.sh --local
./build.sh --system --validate
```

## Issues and contributing

This website refers to all installations and tutorials on Arras Energy's offical GitHub page. If you run into any problems please refer to [Arras Energy GitHub](https://github.com/arras-energy) for more information.
Feel free pull-request your patches and fixes.

## Learn More

Begin your journey by navigating to our Tutorials section, where you can access comprehensive learning materials. Uncover the success stories of Arras Energy's implementation in various Use-Cases. For a deeper understanding, explore our Reports section, offering in-depth literature and relevant news articles.

Start learning and implementing with Arras Energy today, and be part of shaping the future of electricity distribution power systems!
