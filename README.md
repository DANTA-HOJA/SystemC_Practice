# SystemC_Practice
110.2 EEE5009_軟硬體共同設計：自我練習

# Install systemC 

- Download SystemC：[here](https://www.accellera.org/downloads/standards/systemc)

- Install and Test：
    1. To setting systemC on Linux： [Install](https://blog.csdn.net/weixin_44381276/article/details/121641494?spm=1001.2101.3001.6650.9&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-9.pc_relevant_default&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-9.pc_relevant_default&utm_relevant_index=11)

    2. Download the ```CSDN_install_test.cc``` 
    3. Compile ```CSDN_install_test.cc``` using ```g++``` (compile with ```.vscode/task.json``` -> args)
    4. Run ```CSDN_install_test.out```

- If you got ```Error while loading shared libraries: libsystemc-2.3.0.so```：[check here](https://stackoverflow.com/questions/12408882/error-while-loading-shared-libraries-libsystemc-2-3-0-so)

    <div style="height: 30pt"> - Solution： Add ```{where you unzip systemC}/systemc-2.3.3/lib-linux64``` at the end of  ```~/.profile```, using：</div>
    
    ```
    export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:{where you unzip systemC}/systemc-2.3.0/lib-linux64
    ```

# Signal Trace file (.vcd)

- To generate ```*.vcd```：[Example](https://learnsystemc.com/basic/trace)

- To show ```*.vcd```：[GTKWave](http://gtkwave.sourceforge.net/) or other ```*.vcd``` viewer

# Tutorial

1. [Learn SystemC by examples](https://learnsystemc.com/basic/hello_world)

2. [SystemC Tutorial by Doulos](https://www.doulos.com/knowhow/systemc/systemc-tutorial/modules-and-processes/)

3. [Video on Youtube (2013)](https://www.youtube.com/watch?v=NCFxBGLB5xs&list=PLcvQHr8v8MQLj9tCYyOw44X1PLisEsX-J&index=1)