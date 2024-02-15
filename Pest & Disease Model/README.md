dataset_info:
  features:
    - name: image
      dtype: image
    - name: label
      dtype:
        class_label:
          names:
            '0': Spodoptera_litura
            '1': aphid
            '2': beet_armyworm
            '3': borer
            '4': chemical_fertilizer
            '5': cnidocampa_flavescens
            '6': corn_borer
            '7': cotton_bollworm
            '8': fhb
            '9': grasshopper
            '10': longhorn_beetle
            '11': oriental_fruit_fly
            '12': pesticides
            '13': plutella_xylostella
            '14': rice_planthopper
            '15': rice_stem_borer
            '16': rolled_leaf_borer
  splits:
    - name: train
      num_bytes: 163956892.808
      num_examples: 4972
  download_size: 180653939
  dataset_size: 163956892.808
configs:
  - config_name: default
    data_files:
      - split: train
        path: data/train-*