# algorithm-and-pattern-of-dsa
will be adding all the algos i come across daily as for my learning 

# Binary Search Algorithm (Only applied on sorted array )  
       Time Complexity : O(nlogn)

    int BS(vector<int>& nums , int start , int end , int num){

        while(start<=end){

            int mid = (start+end)/2;

            if(nums[mid]==num){

                return mid;

            }else if(nums[mid]>num){

                end= mid-1;
            }else {

                start = mid+1;
            }
        }


    }

#questions based on it 
