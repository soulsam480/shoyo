# Containers <sup> `WIP` </sup>

shoyo containers follow the language of Bootstrap containers i.e. the breakpoints for the responsive containers are same. Also Containers are required while using shoyo [`grid`](/grid). 

shoyo comes with four containers
- `.container` sets 100% width at all breakpoints
- `.c-lg`, `.c-md`, `.c-sm` are modifiers which set `width: 100%` after specified breakpoints
  
## Usage

- `.container` for 100% width
- modifiers with  `.container` e.g. `.container .c-lg` for responsive width at specified breakpoints

### Breakpoints
The table below illustrates how show brekapoints relate to  containers

|              | Small <br/> <small>≥576px</small> | Medium <br/> <small>≥768px</small> | Large <br/> <small>≥992px</small> |
| ------------ | --------------------------------- | ---------------------------------- | --------------------------------- |
| `.container` | 100%                              | 100%                               | 100%                              |
| `.c-lg`      | 100%                              | 100%                               | 960px                             |
| `.c-md`      | 100%                              | 720px                              | 720px                             |
| `.c-sm`      | 540px                             | 540px                              | 540px                             |
 