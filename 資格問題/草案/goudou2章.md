## �ϐ��̐錾
�ϐ��̐錾�Ə��������Đ��������͂ǂ�ł���

1. int num = 100;
1. int num = 100L;
1. int num = "100";
1. int num = 100.0;
1. int num = '100';

`����:1`

## �z��̐錾
�z��̐錾�Ƃ��ėL���Ȃ��͎̂��̂ǂ�ł����B4�I�����Ă��������B

1. int[] array = {1, 2, 3, 4};
1. int[] array = new int[3];
1. int []array = new int[4]{1, 2, 3, 4};
1. int[] array = new int[];
1. int []array = new int[]{1, 2, 3, 4};
1. int array = new int[];
1. int array[3] = new int[];

`����:1,2,5`

## �R�}���h���C�������̗��p
���̃R�[�h������܂��B

```java
public Sample {
  public static void main(String[] args){
    System.out.println(args[0] + args[3]);
  }
}
```

���s����ۂ͎��Ƃ��܂��B

`java Test 1 2`

�R���p�C���A���s�������ʂƂ��Đ��������͎��̂����ǂ�ł����B1�I�����Ă��������B

1. 03 �ƕ\�������
1. 12 �ƕ\�������
1. �R���p�C���G���[�ɂȂ�
1. ���s���G���[�ɂȂ�

`����:4`

## �R�}���h���C�������̗��p2
���̃R�[�h������܂��B

```java
public Sample {
  public static void main(String[] args){
    System.out.println(args[0] + args[3]);
  }
}
```

���s����ۂ͎��Ƃ��܂��B

`java Test args[1] = 10; //������܂���

�R���p�C���A���s�������ʂƂ��Đ��������͎��̂����ǂ�ł����B1�I�����Ă��������B

1. 00 �ƕ\�������
1. 03 �ƕ\�������
1. args[1]//������܂��� �ƕ\�������
1. �R���p�C���G���[�ɂȂ�
1. ���s���G���[�ɂȂ�

`����:3`

## �z��̒���
���̃R�[�h������܂�

```java
public Sample {
  public static void main(String[] args){
    boolean array1 = { true, false, false, false};
    boolean array2 = new boolean[3];
    array2[0] = true;
    array2[1] = true;
    
    System.out.println(array1.length + " " + array2.length);
    
  }
}
```
�R���p�C�����Ď��s�������ʂƂ��Đ��������͂ǂ�ł����B

1. �R���p�C���G���[
1. ���s���G���[
1. 4 3
1. 4 2
1. �����\������Ȃ�

`����:3`

##�R�}���h���C�������̗��p
�R�}���h���C��������p���Ĉȉ��̂悤�ȓ��o�͌��ʂƂȂ�Java�t�@�C�����쐬���Ă��������B

```
> javac Sample.java
> java Sample Hello World
Hello!World
```

