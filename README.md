# AnimeInbet

Original project: [AnimeInbet](https://github.com/lisiyao21/AnimeInbet)

Original author: [lisiyao21](https://github.com/lisiyao2)

Download the data and models as described in the original project.

## Fork Improvements
This fork addresses some major issues found in the original project and allow the testing code run correctly(hopefully). It can generate the inbetweening result now with trigging any error.

## Usage
```python
python -u main.py --config ./configs/cr_inbetweener_full.yaml --gen
```

## Output
The results from this command will be stored in the `./experiments/inbetweener_full/video/epoch20` folder.

**Note**: While the fork is operational and generates results, it may use the training set for output generation. This aspect is uncertain and requires further verification. You are encouraged to modify and adapt the code as needed to suit specific requirements.