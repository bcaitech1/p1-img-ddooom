## Task

사람 얼굴 이미지를 입력 받으면 사람의 마스크 착용 여부, 성별, 나이대를 분류

## Data

사람 얼굴 이미지 (마스크 쓴 것, 안 쓴 것, 부적절하게 쓴 것)


## Training

python train.py 
__python train.py__ 

- config

  1. --model_name
  2. --seed
  3. --age_filter
  4. --p_val
  5. --dataset
  6. --augmentation
  7. --aug_p
  8. --resize
  9. --batch_size
  10. --valid_batch_size
  11. --model
  12. --criterion
  13. --optimizer
  14. --lr
  15. --weight_decay
  16. --lr_scheduler
  17. --lr_decay_step
  18. --epochs
  19. --print_every
  20. --data_dir
