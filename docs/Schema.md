```
graph TD
subgraph Windows
  subgraph WSL
    subgraph Linux
        subgraph Docker tools
        D[Docker]
        DC[Docker Compose]
        end
        subgraph Containers
        C(Container)
        end
        subgraph Visual Studio
          A(Application)
          A-->C
          C-->A  
        end
    end
  end
end
```