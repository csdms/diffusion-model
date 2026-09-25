# diffusion-model

A numerical model used in the [CSDMS Roadshow](https://csdms.colorado.edu/wiki/Roadshows).
See the [project wiki](https://github.com/csdms/diffusion-model/wiki)
for an overview and development plan for the model.

## Install instructions

Set up a virtual environment and install the model into it, along with its dependencies:

```sh
python -m venv venv
source venv/bin/activate
pip install -e .
```

## Examples

After installing the model, run it from a shell prompt with:

```sh
python -m diffusion_model > model.out
```

View the model output:

```sh
cat model.out
```

```console
                                                                            
                                                                            
                              Hillslope profile                             
                                                                            
         ┌──────────────────────────────────────────────────────────┐       
     1.0 ┤                             !!!!!!!!!!!!!!!!!!!!!!!!!!!  │       
         │                             !                            │       
         │                             !                            │       
         │                             !                            │       
     0.8 ┤                             !                            │       
         │                            !                             │       
         │                            !                             │       
         │                            !                             │       
     0.6 ┤                            !                             │       
         │                            !                             │       
    z    │                            !                             │       
         │                            !                             │       
     0.4 ┤                            !                             │       
         │                            !                             │       
         │                            !                             │       
         │                            !                             │       
     0.2 ┤                            !                             │       
         │                            !                             │       
         │                            !                             │       
         │                            !                             │       
         │                            !                             │       
     0.0 ┤  !!!!!!!!!!!!!!!!!!!!!!!!!!!                             │       
         └──┬──────────┬─────────┬──────────┬─────────┬──────────┬──┘       
            0         20        40         60        80         100         
                                                                            
                                      x                                     
                                                                            
                                                                            
                              Hillslope profile                             
                                                                            
         ┌──────────────────────────────────────────────────────────┐       
     1.0 ┤                                          !!!!!!!!!!!!!!  │       
         │                                       !!!                │       
         │                                     !!                   │       
         │                                    !                     │       
     0.8 ┤                                  !!                      │       
         │                                 !!                       │       
         │                                !                         │       
         │                               !!                         │       
     0.6 ┤                              !                           │       
         │                             !!                           │       
    z    │                            !                             │       
         │                            !                             │       
     0.4 ┤                          !!                              │       
         │                          !                               │       
         │                        !!                                │       
         │                        !                                 │       
     0.2 ┤                      !!                                  │       
         │                     !!                                   │       
         │                   !!!                                    │       
         │                 !!!                                      │       
         │           !!!!!!                                         │       
     0.0 ┤  !!!!!!!!!                                               │       
         └──┬──────────┬─────────┬──────────┬─────────┬──────────┬──┘       
            0         20        40         60        80         100         
                                                                            
                                      x                                     
0.000000
0.000133
0.000278
0.000449
0.000659
0.000927
0.001271
0.001714
0.002285
0.003018
0.003951
0.005131
0.006612
0.008457
0.010737
0.013532
0.016931
0.021032
0.025941
0.031770
0.038636
0.046662
0.055970
0.066677
0.078900
0.092743
0.108299
0.125643
0.144829
0.165890
0.188827
0.213615
0.240196
0.268478
0.298337
0.329617
0.362133
0.395672
0.430001
0.464865
0.500000
0.535135
0.569999
0.604328
0.637867
0.670383
0.701663
0.731522
0.759804
0.786385
0.811173
0.834110
0.855171
0.874357
0.891701
0.907257
0.921100
0.933323
0.944030
0.953338
0.961364
0.968230
0.974059
0.978968
0.983069
0.986468
0.989263
0.991543
0.993388
0.994869
0.996049
0.996982
0.997715
0.998286
0.998729
0.999073
0.999341
0.999551
0.999722
0.999867
1.000000
```

## Uninstall instructions

When you're done working with the model, deactivate and delete the virtual environment:

```sh
deactivate
rm -r venv
```

## Contributing

See the [CSDMS contributor guide](https://github.com/csdms/project/blob/main/CONTRIBUTING.md)
for information about contributing to this project.
All contributors are governed by the [CSDMS contributor code of conduct](https://github.com/csdms/project/blob/main/CODE-OF-CONDUCT.md).

## Contact information

To communicate with a human about this project,
visit the [CSDMS Help Desk](https://csdms.colorado.edu/wiki/CSDMS_help_desk)
or sign up for [CSDMS Office Hours](https://csdms.colorado.edu/wiki/OfficeHours).

## Acknowledgments

This work is supported by the U.S. National Science Foundation under
Award No. [2148762](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2148762),
*Collaborative Research: Facility: CSDMS: Engaging a thriving community of practice in Earth-surface dynamics*.
