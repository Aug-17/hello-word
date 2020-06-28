#控制器 {
    位置： 绝对;
    右： 50px ;
    顶部： 10px ;
}

#控制器 div {
    背景：  #ffa5;
    宽度： 24px ;
    高度： 24px ;
    边界半径： 50% ;
    光标： 指针;
    文本对齐 ：中心;
    过渡：所有.2s线性;
    边距顶部： 10px ;
}
#控制器：第一个子级 {
    边距顶部： 0;
}
#控制器 div：悬停 {
    框影 ： 0px  2px  6px   _c;
}
#控制器 div 跨度 {
    颜色： 蔚蓝;
    字体大小： 14px ;
    线高： 24px ;
}

#房东 {
    用户选择 ：无;
    位置： 固定;
    左： 30px ;
    底部： 0;
    z 索引： 10000;
    字体大小： 0;
    过渡：所有 .3的轻松;
    宽度： 560px ;
    高度： 500px ;
}

#Live2d {
    位置： 相对;
    左： 0;
}

.消息 {
    不透明度： 0;
    宽度： 300px ;
    高度： 自动;
    边距 ： 自动;
    填充： 7px ;
    顶部： -20px;
    左： 50% ;
    左边的边距： -150px;
    文本对齐 ：中心;
    边框： 1px固体rgba（255，137，255，.4);
    边框半径 ： 12px ;
    背景色 ： rgba（255，137，255，.2);
    框影 ： 0 3 px  15px  2px rgba  （255，137，255，.4 );
    font-size: 13px;
    字体重量： 400;
    文本溢出：省略号;
    文本转换 ：大写;
    溢出： 隐藏;
    位置： 绝对;
    动画延迟： 5s ;
    动画持续时间： 50s ;
    动画迭代计数 ：无限;
    动画名称 ：摇动;
    animation-timing-function: ease-in-out;
}
@keyframes shake {
    2% {
        transform: translate(0.5px, -1.5px) rotate(-0.5deg);
    }

    4% {
        transform: translate(0.5px, 1.5px) rotate(1.5deg);
    }

    6% {
        transform: translate(1.5px, 1.5px) rotate(1.5deg);
    }

    8% {
        transform: translate(2.5px, 1.5px) rotate(0.5deg);
    }

    10% {
        transform: translate(0.5px, 2.5px) rotate(0.5deg);
    }

    12% {
        transform: translate(1.5px, 1.5px) rotate(0.5deg);
    }

    14% {
        transform: translate(0.5px, 0.5px) rotate(0.5deg);
    }

    16% {
        transform: translate(-1.5px, -0.5px) rotate(1.5deg);
    }

    18% {
        transform: translate(0.5px, 0.5px) rotate(1.5deg);
    }

    20% {
        transform: translate(2.5px, 2.5px) rotate(1.5deg);
    }

    22% {
        transform: translate(0.5px, -1.5px) rotate(1.5deg);
    }

    24% {
        transform: translate(-1.5px, 1.5px) rotate(-0.5deg);
    }

    26% {
        transform: translate(1.5px, 0.5px) rotate(1.5deg);
    }

    28% {
        transform: translate(-0.5px, -0.5px) rotate(-0.5deg);
    }

    30% {
        transform: translate(1.5px, -0.5px) rotate(-0.5deg);
    }

    32% {
        transform: translate(2.5px, -1.5px) rotate(1.5deg);
    }

    34% {
        transform: translate(2.5px, 2.5px) rotate(-0.5deg);
    }

    36% {
        transform: translate(0.5px, -1.5px) rotate(0.5deg);
    }

    38% {
        transform: translate(2.5px, -0.5px) rotate(-0.5deg);
    }

    40% {
        transform: translate(-0.5px, 2.5px) rotate(0.5deg);
    }

    42% {
        transform: translate(-1.5px, 2.5px) rotate(0.5deg);
    }

    44% {
        transform: translate(-1.5px, 1.5px) rotate(0.5deg);
    }

    46% {
        transform: translate(1.5px, -0.5px) rotate(-0.5deg);
    }

    48% {
        transform: translate(2.5px, -0.5px) rotate(0.5deg);
    }

    50% {
        transform: translate(-1.5px, 1.5px) rotate(0.5deg);
    }

    52% {
        transform: translate(-0.5px, 1.5px) rotate(0.5deg);
    }

    54% {
        transform: translate(-1.5px, 1.5px) rotate(0.5deg);
    }

    56% {
        transform: translate(0.5px, 2.5px) rotate(1.5deg);
    }

    58% {
        transform: translate(2.5px, 2.5px) rotate(0.5deg);
    }

    60% {
        transform: translate(2.5px, -1.5px) rotate(1.5deg);
    }

    62% {
        transform: translate(-1.5px, 0.5px) rotate(1.5deg);
    }

    64% {
        transform: translate(-1.5px, 1.5px) rotate(1.5deg);
    }

    66% {
        transform: translate(0.5px, 2.5px) rotate(1.5deg);
    }

    68% {
        transform: translate(2.5px, -1.5px) rotate(1.5deg);
    }

    70% {
        transform: translate(2.5px, 2.5px) rotate(0.5deg);
    }

    72% {
        transform: translate(-0.5px, -1.5px) rotate(1.5deg);
    }

    74% {
        transform: translate(-1.5px, 2.5px) rotate(1.5deg);
    }

    76% {
        transform: translate(-1.5px, 2.5px) rotate(1.5deg);
    }

    78% {
        transform: translate(-1.5px, 2.5px) rotate(0.5deg);
    }

    80% {
        transform: translate(-1.5px, 0.5px) rotate(-0.5deg);
    }

    82% {
        transform: translate(-1.5px, 0.5px) rotate(-0.5deg);
    }

    84% {
        transform: translate(-0.5px, 0.5px) rotate(1.5deg);
    }

    86% {
        transform: translate(2.5px, 1.5px) rotate(0.5deg);
    }

    88% {
        转换：转换（-1.5px， 0.5px）旋转（1.5deg );
    }

    90% {
        转换：转换（-1.5px， -0.5px）旋转（-0.5deg );
    }

    92% {
        转换：转换（-1.5px， -1.5px）旋转（1.5deg );
    }

    94% {
        转换：转换（0.5px， 0.5px）旋转（-0.5deg );
    }

    96% {
        转换：转换（2.5px， -0.5px）旋转（-0.5deg );
    }

    98% {
        转换：转换（-1.5px， -1.5px）旋转（-0.5deg );
    }

    0%， 100% |
        转换：转换（0， 0）旋转（0);
    }
}
