## INTERPOLATION

<h1>{{pageTitle}}</h1>
<h1 innerText={{pageTitl}}></h1>  * note with interpolation the quotes are not needed
{{'Title: ' + pageTitle}}
{{'Title: ' + getTitle()}}
{{2*20+1}}

## Structural direvative

*ngIf *ngFor are exposed by BrowserModule

** for of vs for in

for nickName of nickNames
console.log(nickName)
di doo punkeye

for nickName in nickNames
console.log(nickName)
0 1 2

## lifecycle

OnInit
OnChanges
OnDestroy

* ngOnChanges() only watches changes of Input

## Output
the eventEmitter is from angular/core