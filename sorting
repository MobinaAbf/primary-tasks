#include <iostream>
using namespace std;

class Sort
{
    int *array;
    int size;
    int temp;

    public:
    void input();
    void BubbleSort();
    void InsertionSort();
    void SelectionSort();
    void QuickSort();
    void HeapSort();
    void MergeSort();

};

//=============================================


void Sort::input(){
    
    cout<<"Enter size of array \n";
    cin>>size;
    
    array=new int[size];
    for(int i=0;i<size;i++){
        cout <<"array ["<<i<<"] : ";
        cin>>array[i];
    }
}

//=============================================

void Sort::BubbleSort(){

    for(int i=n-1; i<=0; i--){
        for(int j=0; j<i; j++)
        if(array[j]>array[j+1]){
            temp=array[j];
            array[j]=array[j+1];
            array[j+1]=temp;
        }
    }
}

//=============================================

void Sort::InsertionSort(){
    
    for(int i=1; i<n; i++){
        int j= i-1;
        temp=array[i];
        
        while(array[j]>temp && j>=0){
            array[j+1]=array[j];
            j--;
        }
        array[j+1]=temp;
    }
}

//=============================================

void Sort::SelectionSort(){
    
    int min,k;
    for(int i=0; i<n; i++){
        min=array[i];
        k=i;
        
        for(int j=i+1; j<n; j++){
            min=array[j];
            k=j;
        }
        array[k]=array[i];
        array[i]=min;
    }
}

//=============================================

void Sort::QuickSort(){
    
}



int main(){
    int x;
    Sort S;
    S.input();

    cout<<"Choose the method \n ";
    cout<<"1_Bubble Sort \n";
    cout<<"2_Insertion Sort \n";
    cout<<"3_Selection Sort \n";
    cout<<"4_Quick Sort \n";
    cout<<"5_Heap Sort \n";
    cout<<"6_Merge Sort \n";
    cin>>x;

    switch (x)
    {
    case 1:
        /* code */
        break;
    
    default:
        break;
    }
}
   
